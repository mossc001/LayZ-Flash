# LayZ-Flash
## Lay-Z-Spa Flashing Tool

If you have purchased or have a **Lay-Z-Spa DIY WiFi Controller - 6-Pin or 4-Pin Version**, then you can use this tool to reflash it in the instance of fault, corruption, or to update to the latest version/release. If you wish to purchase a Lay-Z-Spa DIY WiFi Controller (6-Pin Version), you can purchase them via; https://www.ebay.co.uk/usr/mossc001

Requirements: Windows 10 or higher with an available USB port.

1. To flash your ESP Lay-Z-Spa module, download the ZIP file and unzip to a location on your Desktop or Local C Drive; https://github.com/mossc001/LayZ-Flash/releases

<img src="https://github.com/mossc001/LayZ-Flash/blob/main/v1.1.0_flashing-tool_window.png" width="700">

2. Connect your ESP to your computer/laptop using a Micro-USB data cable; ensure that it's a data cable and not a phone charging cable.

3. Wait for a 1-2 minutes for the drivers to be installed for the ESP by Windows otherwise the flashing file won't see the device!

4. Double click the "upload.bat" file; Windows may prompt you as it's an unrecognised Application. Click "More Info", then click "Run anyway" on the proceeding screen.

<img src="https://github.com/mossc001/LayZ-Flash/blob/main/flashing_tool_protected.jpg" width="700">

5. Once permissions have been granted, it will open a Command Prompt and flash the ESP. DO NOT disconnect or close the window whilst it is flashing.

<img src="https://github.com/mossc001/LayZ-Flash/blob/main/v1.1.0_flashing-tool_command.png" width="700">

6. Wait for the process to finish; the window will close itself.

7. Unplug your ESP from your computer, and plug it in again. Go to the Webpage of the ESP via it's DHCP IP (or http://layzspa.local) or in later versions (after version 1.2.5) go to http://192.168.4.2/wifi.html and verify the upload is successful.

8. Configure your device via the DHCP IP (pre-version 1.2.5) or via http://192.168.4.2/wifi.html (after version 1.2.5). _ _ Note: If connecting to the from a Mobile Device, you may need to disabnle "Private WiFi-Address" in your phone settings to be able to access the IP address of the ESP Lay-Z-Spa module. _ _ 

9.  After configuring to your local WiFi AP, access it via the IP assigned by your local network. 

If the above does not work correctly, try again as Windows may still be installing the drivers for the ESP COM port.

## Credits:
https://github.com/visualapproach for the original Lay-Z-Spa build.
