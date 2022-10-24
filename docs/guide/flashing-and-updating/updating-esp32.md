---
sidebarDepth: 1
next: ../multiple-adapters-setup/
---

# Updating ESP32
## Updating ESP32 Over the Air (distantly)

If your SLZB-06 device has a LAN connection, you can update the ESP32 firmware remotely via Over-the-Air (OTA) updates feature. To update the firmware via OTA, follow these steps:
1. Download the latest firmware from [official SLZB-06 Firmware repository](https://github.com/smlight-dev/slzb-06-firmware/);
2. Go to the web interface of the device;
3. Go to the System and Tools section. In the "ESP32 Update" card 
- click Choose file;
- select the firmware (*.bin file) and
- Click ESP32 OTA Update.
<img src="../../images/fw/systemtools-esp32-flash-rounded.png" title="SLZB-06 Firmware - System flash tools - ESP32 flashing" class="float-left" />
4. Wait for the firmware to finish and reboot the device

## Updating ESP32 via USB
If your SLZB-06 device is not connected to LAN or you want to flash ESP32 via USB for other reasons, it can be easily done via USB cable. For this purposes you need:
- A computer with Windows or Mac installed;
- USB - Type-C cable.

To flash via USB, follow these steps:
1. Download the flashing software. We recommend using ESP_Flasher, which can be downloaded from [this official link at Github](https://github.com/Jason2866/ESP_Flasher);
2. Download the latest firmware version from [official SLZB-06 Firmware repository](https://github.com/smlight-dev/slzb-06-firmware/);
3. Using USB cable, connect SLZB-06 to your computer;
4. Run the ESP_Flasher program and
- Select Serial-port in the Serial port section;
- In the Firmware section, select the file with your firmware;
- Press the "Flash ESP" button.
5. Wait for the firmware to complete.


## Updating ESP32 via DIY pinouts
