# 🛠️ R4TKN 🔥 Wi-Fi Warfare Toolkit for Flipper Zero + BW16

This firmware turns your Flipper Zero (paired with BW16) into a powerful Wi-Fi testing device.  
Includes tools like **DEAUTH ALL**, **Targeted Disruption (Per Station / Client)**, with upcoming features like **Random SSID Spam**, **Beacon Floods**, and **Handshake Capture**.  
Perfect for Wi-Fi experiments, stress testing, and educational network security research.

## Check Some Updates ? Join our Telegram 
https://t.me/+2b0bppqzackxZTg1

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X8X71M0J84)

> ⚠️ **Important Note**  
> 🔴 It **may not function properly on modern 5GHz routers/modems**, which are not vulnerable to typical deauth or beacon flood techniques due to band separation and stricter security protocols.


> ⚠️ **License & Disclaimer**  
> This software is provided "as-is" for educational and research use only. The author disclaims all liability for misuse or damage incurred from its use. Always obtain proper authorization before testing any network security tool.

## ⚠️ Known Issues

> ❗ **Compatibility Notice**  
> "It's not working on the other Flipper Zero BW16 Dev Board from Aliexpress or other store."

Some third-party BW16 dev boards (often sold on AliExpress/other marketplaces) may use different pin mappings, bootloaders, or power/level shifting that **breaks flashing or runtime behavior** with this firmware.

## Acknowledgements

 - [cypher-5G-deauther - dkyazzentwatwa](https://github.com/dkyazzentwatwa/cypher-5G-deauther/tree/mainawesome-README-templates)

 - [delfyRTL](https://github.com/gorebrau/delfyRTL/tree/main)
 - [flipper-zero-tutorials](https://github.com/jamisonderek/flipper-zero-tutorials)

 - [lopaka - sbrin](https://github.com/sbrin/lopaka)

 - [ambd_sdk](https://github.com/ambiot/ambd_sdk) Image Tool

 - [readme.so](https://github.com/octokatherine/readme.so)



⚠️ **Available Internationally**  
 - This is already have an full working version of this firmware , not this repo
 - Buy Here: [Elecrow](https://www.elecrow.com/flipper-zero-bw16-rtl8720dn-dual-band-wifi-board.html)

## Features

- ✅ **DEAUTH ALL**  
  Disconnect all nearby Wi-Fi devices from their networks.

- ✨ **TARGETED – PER STATION and PER CLIENT**  
  Choose a specific Access Point (Station) or a connected device (Client) to target.  
  _→ Other devices will NOT be affected._

---

## 🛠️ Upcoming / TODO Features

- 🚧 **RANDOM SSID** *(In Progress)*  
  Will flood the air with randomly generated fake Wi-Fi names (SSIDs) to confuse nearby scanners.

- 🚧 **BEACON + DEAUTH** *(In Progress)*  
  Will send fake beacon frames with deauth packets to simulate chaotic Wi-Fi environments.

- 🚧 **NRF24 + 2.4GHZ (NO EXTRA ESP32)** *(In Progress)*  
  🔥 BLE JM + WIFI JAM for 2.4 + 5GHZ DEAUTH 🔥

- 🚧 **CAPTURE HANDSHAKE** *(Planned)*  
  Will enable WPA/WPA2 handshake capturing for research and testing.
  
- 🔧 **MORE SOON**  
  Additional tools and experimental features coming soon!
## 🔌 Pin Mapping: RTL8720DN BW16 ↔ Flipper Zero

| RTL8720DN BW16 | Flipper Zero |
|----------------|--------------|
| 5V             | (1) 5V       |
| GND            | (8) GND      |
| RX1            | (13) TX      |
| TX1            | (14) RX      |

> 📎 Pinout reference credits: [gorebrau/delfyRTL](https://github.com/gorebrau/delfyRTL)





## How to Upload Firmware 

## WEB FLASHER 

[FLASH HERE](https://flasher.rusprojects.com/)

![](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/Screenshot/online-flasher.png)

### 📥 Flashing Instructions (BW16)
![](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/Screenshot/flasher1.png)

## ⚠️ Important Note

For those who already have an existing firmware installed on their BW16, it is recommended to erase the existing firmware first before flashing a new one. This helps avoid conflicts and ensures a clean installation.

1. **Run as Administrator**  
   - Right-click the **R4TKN FLASHER** and select `Run as administrator`.

3. **Configure Serial Port**  
   - Go to the `COM Port` section.  
   - Under `COM`, select the correct port for your connected **BW16**.  
   - Leave the rest of the settings as default.

5. **Put BW16 in Flash Mode & Start Flashing**  
   - If your BW16 is **not already in flash mode**, do the following:  
     - Hold the **BOOT** button.  
     - While holding BOOT, **press and release RESET**.  
     - Release the BOOT button.  
     - The BW16 is now in **flash mode**.  
   - Now click the `Run Upload` button to flash the firmware.

### 🛠 Step-by-Step Instructions for Flipper Zero

1. **Install and Launch qFlipper**  
   - Visit the official qFlipper page and download the installer for your OS.  https://flippeprzero.one/update
   - Install and then open **qFlipper**.  
   - Connect your Flipper Zero via USB-C to your PC.

2. **Open the File Manager**  
   - In qFlipper, click the **“File manager”** tab to view the contents of your Flipper’s SD card.

3. **Locate or Create the `apps` Folder**  
   - Navigate to the `apps` directory on your SD card.  
   - If it doesn’t exist, **right-click** on the SD root and select **“New folder”**, then name it `apps`.

4. **Copy the `.fap` File**  
   - **Drag & drop** your `.fap` file directly into the `apps` folder via qFlipper, or  
   - **Right-click → Upload** to select and add it manually.

5. **Verify on the Flipper**  
   - On your Flipper device, navigate: **Applications → FAP Loader**.  
   - You should now see and be able to launch your newly added app.

## 📬 Support / Collaboration

Got questions, ideas, or want to collaborate?  
Drop an email at **web.r4tkn@gmail.com**

[![Buy Me a Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](http://coff.ee/rusn)
## Screenshots

![](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/Screenshot/1.png)
![](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/Screenshot/4.png)
![](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/Screenshot/7.png)


## PCB  

📦 Local Stocks Available! 🇵🇭 Philippines, 🇸🇬 Singapore, 🇲🇾 Malaysia
📦 Stocks Available Internationally via Buy Here: [Elecrow](https://www.elecrow.com/flipper-zero-bw16-rtl8720dn-dual-band-wifi-board.html)

![PCB](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/PCB/10.png)
![PCB](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/PCB/8.png)
![PCB](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/PCB/9.png)



