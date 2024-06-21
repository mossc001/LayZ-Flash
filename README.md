# LayZ-Flash
## Lay-Z-Spa Flashing Tool

If you have purchased or have a **Lay-Z-Spa DIY WiFi Controller - 6-Pin or 4-Pin Version**, then you can use this tool to reflash it in the instance of fault, corruption, or to update to the latest version/release. If you wish to purchase a Lay-Z-Spa DIY WiFi Controller (6-Pin Version), you can purchase them via; https://www.ebay.co.uk/usr/mossc001

Requirements: Windows 10 or higher with an available USB port.

1. To flash your ESP Lay-Z-Spa module, download the ZIP file and unzip to a location on your Desktop or Local C Drive; https://github.com/mossc001/LayZ-Flash/releases

<img src="https://github.com/mossc001/LayZ-Flash/blob/main/v1.1.0_flashing-tool_window.png" width="700">

2. Connect your ESP to your computer/laptop using a Micro-USB data cable; ensure that it's a data cable and not a phone charging cable.

3. Wait for a 1-2 minutes for the drivers to be installed for the ESP by Windows otherwise the flashing file won't see the device!

4. Double click the "upload.bat" file, give permissions to run, then it will open a Command Prompt and flash the ESP. DO NOT disconnect or close the window whilst it is flashing.

<img src="https://github.com/mossc001/LayZ-Flash/blob/main/v1.1.0_flashing-tool_command.png" width="700">

5. Wait for the process to finish; the window will close itself.

6. Unplug your ESP from your computer, and plug it in again. Go to the Webpage of the ESP via it's DHCP IP and verify the upload is successful.

If the above does not work correctly, try again as Windows may still be installing the drivers for the ESP COM port.

## Credits:
https://github.com/visualapproach for the original Lay-Z-Spa build.
