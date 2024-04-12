**SETUP PROCEDURE FOR RUCKUS UNLEASHED**
1. Login to Unleashed
2. Go to: Admin & Services > Services > Wi-Fi Calling > Select Profiles tab > Press +Create to create a new profile.
3. Within the Create New window navigate to the General section and configure per below. 
        General:  
        - Name: Name your profile (e.g. Bell), create a profile for each carrier.  
        - Description: Wi-Fi Calling Profile  
        - QoS Priority = Voice  
        Under Evolved Packet Data Gateway (eDPG):  
        - Press Create New
        - Enter Domain Name and IP Address per below and click Save
    
4. Leave the Admin & Services section and navigate to Wi-Fi Networks and select the network you want to enable Wi-Fi calling for. Press the Edit above to configure that WLAN.
    
5. Edit WLAN window  
         Clock on Show Advanced Options to expand menu > Select Access Control and enable the Wi-Fi Calling checkbox.  
         Click the Edit button and select each profile under you created in (2) under Available Profiles and press the right arrow to place that profile into the Selected Profiles group.  
    Repeat (4) and (5) as needed for any additional networks needing Wi-Fi calling enabled for (e.g. Guest network). Congrats! You've just configured WiFi Calling on your Access Point(s).
