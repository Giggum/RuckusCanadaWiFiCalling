Setup\
1. Login to Unleashed:\
&nbsp;&nbsp;&nbsp;&nbsp; Go to: Admin & Services > Services > Wi-Fi Calling > Select Profiles tab > Press +Create to create a new profile

2. Create New window\
&nbsp;&nbsp;&nbsp;&nbsp; General:\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Name: Name your profile (e.g. Bell), create a profile for each carrier.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Description: Wi-Fi Calling Profile\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; QoS Priority = Voice\
&nbsp;&nbsp;&nbsp;&nbsp; Under Evolved Packet Data Gateway (eDPG):\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Press Create New\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Enter Domain Name and IP Address per below and click Save

3. Leave Admin & Services and navigate to Wi-Fi Networks and select the network you want to enable Wi-Fi calling for. Press the Edit above to configura that WLAN.
4. Edit WLAN window\
&nbsp;&nbsp;&nbsp;&nbsp; Clock on Show Advanced Options to expand menu > Select Access Control and enable the Wi-Fi Calling checkbox.\
&nbsp;&nbsp;&nbsp;&nbsp; Click the Edit button and select each profile under you created in (2) under Available Profiles and press the right arrow to place that profile into the Selected Profiles group.\
&nbsp;&nbsp;&nbsp;&nbsp; Repeat (3) and (4) as needed for any additional networks needing Wi-Fi calling enabled for (e.g. Guest network).
<br>

| Carrier Name               | Domain Name                                  | IP Address     |
| ---------------------------| -------------------------------------------  |----------------|
| Bell                       | epdg.epc.mnc610.mcc302.pub.3gppnetwork.org   | 69.158.242.2   |
| Rogers                     | epdg.epc.mnc720.mcc302.pub.3gppnetwork.org   | 209.148.157.48 |
| Rogers / Fido              | epdg.epc.mnc370.mcc302.pub.3gppnetwork.org   | 209.148.157.48 |
| Telus                      | epdg.glbpr.mnc220.mcc302.pub.3gppnetwork.org | 207.219.233.33 |
| Videotron                  | epdg.epc.mnc510.mcc302.pub.3gppnetwork.org   | 184.163.5.80   |
| Videotron / Freedom Mobile | epdg.epc.mnc490.mcc302.pub.3gppnetwork.org   | 74.115.197.33  |

For additional info see: https://docs.commscope.com/bundle/unleashed-200.14-onlinehelp/page/GUID-996C0981-4172-4FB6-AD95-A49E8B64D0F6.html
