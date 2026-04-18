# Lay-Z-Spa Module Setup
## Quick Setup

If you have purchased or have a **Lay-Z-Spa DIY WiFi Controller - 6-Pin or 4-Pin Version**, then you can use this guide to quickly get your module setup for your pump.

### Disclaimer:
This is a modification; if anything breaks or invalidates your warranty, I cannot accept liability.

### !! WARNING !!
- WARNING - Electric Shock Can Kill!!!
- Touching live electrical parts can cause fatal shocks or severe burns.
- Pull out the mains plug from the outlet before modifying any hardware.
- You undertake this at your own risk.

### Quick Connection Setup

We recommend configuring the device offline before connecting to the pump!

1.	Power the module via a stable USB powered connection e.g. from a phone charger. Once powered up, the blue light will constantly flash on the module.
2.	On your phone or any other device with WiFi, you will need to connect to the module via it’s WiFi Access Point. When browsing for WiFi networks, you should see an Access Point is created called "Lay-Z-Spa Module#####".
3.	To connect to this, you will need the password which is **layzspam0dule**
4.	Then open a browser and enter address http://192.168.4.2/wifi.html
> Note: If connecting to the from a Mobile Device, you may need to disable "Private WiFi-Address" in your phone settings to be able to access the IP address of the ESP Lay-Z-Spa module.
6.	Fill in the credentials for your own home WiFi network e.g. the one you want to the module to connect to, then press “Save”. Wait a few seconds and restart the module.
7.	If the module can connect to your Wi-Fi, it will shut down its own access point. You can connect to your own home WiFi network with your phone again.
8.	If successful, you can browse to the module on your home WiFi network, via http://layzspa.local

### Pump Setup

Do not connect to the pump yet, you should setup the hardware config and other settings! From the http://layzspa.local, go to...

1. Go to "Hardware Config" and set the pump model and display model. For the 6-pin it will typically be the "6-wire, ######".
2. Staying within "Hardware Config", set the PCB to "V2B", then press "Save".
3. Once set, then disconnect from the USB, and connect to the pump. If the display does not light up but the module is accessible via http://layzspa.local, then the pump model/display model is incorrect in the settings. If incorrect, go back and try another pump model and display model.

## Credits:
https://github.com/visualapproach for the original Lay-Z-Spa build.
