**SETUP PROCEDURE FOR RUCKUS UNLEASHED**
1. Login to Unleashed
2. Go to: Admin & Services > Services > Wi-Fi Calling > Select Profiles tab > Press +Create to create a new profile.

3. Within the Create New window navigate to the General section and configure per below.
   * Name: Name your profile (e.g. Bell)
   * Description: Wi-Fi Calling Profile  
   * QoS Priority: Voice\

   Under Evolved Packet Data Gateway (eDPG):
   * Press Create New
   * For the carrier of your choice, enter their Domain Name and IP Address from the "ruckus_canadian_wifi_calling.md" page. Click Save
   * Repeat above two steps for each additional carrier you want to add.
    
5. Leave the Admin & Services section and navigate to Wi-Fi Networks and select the network you want to enable Wi-Fi calling for. Press the Edit button above to configure that WLAN.
    
6. Edit WLAN window
   * Click on Show Advanced Options to expand the menu > Select Access Control and enable the Wi-Fi Calling checkbox.
   * Click the Edit button and select each profile that you created in (3) that's listed under Available Profiles and press the right arrow to place that profile into the Selected Profiles group. Click OK to leave the Wi-Fi Calling Profile. Click OK to leave the edit WLAN page. 

Repeat (5) and (6) as needed for any additional networks needing Wi-Fi calling enabled for (e.g. Guest network).

Congrats! You've just configured WiFi Calling on your Access Point(s).
