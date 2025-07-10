# ESP8266-Deauther

This project is an ESP8266 deauther that can be controlled via the web.  
I assembled the hardware and used open source code from [SpacehuhnTech](https://github.com/SpacehuhnTech).

## Feature
- Deauth : Closes the connection of WiFi devices by sending deauthentication frames to access points and client
					devices you selected.
- Beacon : Beacon packets are used to advertise access points. By continuously sending beacon packets out, it
					will look like you created new WiFi networks.
- Probe : Probe requests are sent by client devices to ask if a known network is nearby.<br>
					Use this attack to confuse WiFi trackers by asking for networks that you specified in the SSID
					list.

## Documentation
Harware view
- [Front look](Documentation/Deauther_front.jpeg)
- [Back look](Documentation/Deauther_back.jpeg)

Attack
- [Deauth](Documentation/Deauth.jpeg)
- [Beacon](Documentation/Beacon.jpeg)
- Probe (i`m sorry, i do not have documentation for this)

## Credit 🙏
- Software and code in this project is from:
[esp8266_deauther](https://github.com/SpacehuhnTech/esp8266_deauther/) from [SpacehuhnTech](https://github.com/SpacehuhnTech) – Under MIT license
- Hardware : Frentis Radytia P.

## License 
MIT License
