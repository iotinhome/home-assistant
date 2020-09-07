
[Gallery](https://www.iotinhome.com/gallery) | [Blog](https://www.iotinhome.com/blog) | [Facebook](https://www.facebook.com/IOTinHome-108633134217001) | [YouTube](https://www.youtube.com/channel/UCG5HGYPUQp9z4KuTIpBlC0A) | [Twitter](https://twitter.com/iotinhome1)


FloorPlan
---------

![FloorPlan](https://github.com/iotinhome/home-assistant/blob/master/www/Floorplan.PNG)

ZWAVE
-----
Recently migrated from Vera to a Zooz USB Stick on the PI4. The network is stable and reliable. OZW is still in beta and some that will be considered in future. 
![ZWAVE Network Map](https://github.com/iotinhome/home-assistant/blob/master/www/zwave%20network3.PNG)

Automation
----------
- [Movie time](https://youtu.be/6z-h19JVmxA) - Switch off multiple lights, switch on backlight LEDs and TV, using Zwave and wyze api calls and Wake on LAN for TV.
- [Ohm Shutdown](https://youtu.be/sgi07IzKXCA) - Powers down multiple devices, based on a trigger from the service.
- [Coffee Machine](https://twitter.com/iotinhome1/status/1300687736685420552) - Unplugging the smartphone in the morning triggers the automation.
- [Lock Front Door](https://github.com/iotinhome/home-assistant/blob/master/automations.yaml) - Lock the front door after 2 minutes.
- [Kitchen lights off](https://github.com/iotinhome/home-assistant/blob/master/automations.yaml) - Turn the lights off, if no motion detected after 5min. Wyze motion sensor and Wyze wifi plug.
- [Sunset in 1 hour](https://github.com/iotinhome/home-assistant/blob/master/automations.yaml) - Google Mini voice notification
- [Away - Thermostat](https://github.com/iotinhome/home-assistant/blob/master/automations.yaml) - Lower the thermostat, based on presence detection

Automations have additional conditions for time of day. 

Presence detection
-------------
Currently using ping sensor on the primary smartphone, with a static DHCP and this seems reliable.
Config files have comments for the other options that have been attempted in the past. 

LED light - budget solution
----------
Using a $13 (no smart LED might strip), which is plugged into a wyze wifi plug (~$10) that does the on/off automation, based on motion or other scripts. 

Notifications
------------
- [Twilio](https://github.com/iotinhome/home-assistant/blob/master/notify.yaml)
- [Email](https://github.com/iotinhome/home-assistant/blob/master/notify.yaml)

HACS/Custom components
----
[Link](https://github.com/iotinhome/home-assistant/tree/master/custom_components)

Themes
----
[Link](https://github.com/iotinhome/home-assistant/tree/master/themes)

Articles
--------
-   [Companies and Products](https://www.iotinhome.com/article1)
-   [UPS Battery Backup](https://www.iotinhome.com/upsreview) - - Network UPS Tools Add-on
-   [Do you still have a fax line ?](https://www.iotinhome.com/landline)
-   [My Smart home Setup](https://www.iotinhome.com/mysmarthome) 


Cameras
-------
Foscam, Amcrest, WyzeCam v2, Wyzecam Pan
![Camera](https://github.com/iotinhome/home-assistant/blob/master/www/camera-night.PNG)

SIM Card
--------
[Link](https://amzn.to/2ZhlVYV)



My Smart Home Devices
---------------------

| Vera Contoller      |Smart Switch Energy      |  Zwave Plug      |
|------------|------------|-----------|
|[![Vera Controller](https://github.com/iotinhome/home-assistant/blob/master/www/pic-2-vera.PNG)](https://amzn.to/3lJxd1D)|[![Smart Switch Energy](https://github.com/iotinhome/home-assistant/blob/master/www/pic-1-smartswitch.PNG)](https://amzn.to/32NlFBY)|[![Zwave Plug](https://github.com/iotinhome/home-assistant/blob/master/www/pic-3-plug.PNG)](https://amzn.to/3hZbd0A)|
| Zwave Light Dimmer      | Zwave Thermostat      |  Zwave Switch      |
|[![Zwave Light Dimmer](https://github.com/iotinhome/home-assistant/blob/master/www/pic-4-GE-light-dimmer.PNG)](https://amzn.to/2GiNZVa)|[![Zwave Thermostat](https://github.com/iotinhome/home-assistant/blob/master/www/pic-5-thermostat.PNG)](https://amzn.to/3jKqoLJ)|[![Zwave Switch](https://github.com/iotinhome/home-assistant/blob/master/www/pic-6-zwave-switch.PNG)](https://amzn.to/2Z15UGl)|
| Zwave Fibaro Sensor      |Zwave Door Sensor      |  Zwave Yale Door Lock      |
|[![Zwave Fibaro Sensor](https://github.com/iotinhome/home-assistant/blob/master/www/pic-9-fib-1.PNG)](https://amzn.to/2ESVge3)|[![Zwave Door Sensor](https://github.com/iotinhome/home-assistant/blob/master/www/pic-8-zwave-door-sensor.PNG)](https://amzn.to/35d90LF)|[![Zwave Yale Door Lock](https://github.com/iotinhome/home-assistant/blob/master/www/pic-7-yale-1.PNG)](https://amzn.to/2Z0vVpr)|
| Zwave Scene Controller      |  Zwave Yale DeadBolt      |  Zwave Flood Sensor      |
|[![Zwave Scene Controller](https://github.com/iotinhome/home-assistant/blob/master/www/pic-10-scene-zwave.PNG)](https://amzn.to/34ZdDso)|[![Zwave Yale DeadBolt](https://github.com/iotinhome/home-assistant/blob/master/www/pic-11-yale-zwave-deadbolt.PNG)](https://amzn.to/3lV8NTc)|[![Zwave Flood Sensor](https://github.com/iotinhome/home-assistant/blob/master/www/pic-12-fib-flood-zwave.PNG)](https://amzn.to/3bmFyDE)|
| Wyze Wifi Plug      |  Zooz zwave Stick - USB      |  LED light strip      |
|[![Wyze Wifi Plug](https://github.com/iotinhome/home-assistant/blob/master/www/pic-13-wyze-plug.PNG)](https://amzn.to/2GqvoXq)|[![Zooz zwave Stick - USB](https://github.com/iotinhome/home-assistant/blob/master/www/pic-14-zooz.PNG)](https://amzn.to/2QP9bUT)|[![LED light strip](https://github.com/iotinhome/home-assistant/blob/master/www/pic-15-led.PNG)](https://amzn.to/2GqMPXR)|
| USB Hub      |  WyzeCam      |  Echo Dot      |
|[![USB Hub](https://github.com/iotinhome/home-assistant/blob/master/www/pic-16-hub-usb.PNG)](https://amzn.to/3gVvLFN)|[![WyzeCam](https://github.com/iotinhome/home-assistant/blob/master/www/pic-17-wyzecam.PNG)](https://amzn.to/3bqPxb7)|[![Echo Dot](https://github.com/iotinhome/home-assistant/blob/master/www/pic-18-echo-dot.PNG)](https://amzn.to/3jL9wEC)|
| Raspberry PI kit      |  USB SATA Connector      |  SSD Drive      |
|[![Raspberry PI kit](https://github.com/iotinhome/home-assistant/blob/master/www/pic-19-pi4.PNG)](https://amzn.to/3lL0qJT)|[![USB SATA connector](https://github.com/iotinhome/home-assistant/blob/master/www/pic-20-sata.PNG)](https://amzn.to/2QXg0DG)|[![SSD Drive](https://github.com/iotinhome/home-assistant/blob/master/www/pic-21-SSD.PNG)](https://amzn.to/2DynhXO)||


System Stats
-------------
![Utilization](https://github.com/iotinhome/home-assistant/blob/master/www/sysinfo-1.PNG)

Some of the links in this post are affiliate links. This means if you click on the link and purchase the item, I will receive an affiliate commission at no extra cost to you. All opinions remain my own.

-   [Facebook](https://www.facebook.com/IOTinHome-108633134217001)
-   [Youtube](https://www.youtube.com/channel/UCG5HGYPUQp9z4KuTIpBlC0A)
-   [Twitter](https://twitter.com/iotinhome1)
