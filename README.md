# v2ray-box
A lightweight device for managing V2Ray proxy services with advanced features like load balancing and client control.

## Features
1. **Easy-to-configure V2Ray proxy management.**
2. **Load balancing between proxies.**
3. **Lightweight hardware and efficient software integration.**
4. **NAT support for seamless network sharing.**
5. **Wireless Access Point** - Provides a secure wireless access point for connecting devices to unrestricted internet.
7. **User-Friendly Panel** - Includes an intuitive web panel for managing V2Ray accounts and configurations.
9. **Transparent Proxy** - Transparent proxy on the wireless network eliminates the need for manual proxy configuration on clients.
11. **Preconfigured Image** - A fully preconfigured and compressed disk image is provided, containing all the necessary settings for seamless operation.
13. **OpenWRT Integration** - Offers access to the OpenWRT web panel for changing initial settings like WiFi name and password.

## Requirements
To set up and use the **v2ray-box**, you will need the following hardware and software:

#### **Hardware:**
1. **Computer with Windows** – Required to flash the image file onto the micro SD card.
2. **Raspberry Pi 3B+** – The main hardware to run the v2ray-box software.
3. **Micro SD Card** (at least 2GB, Class 10 recommended) – To store the image file.
4. **SD Card Reader** – For transferring the image file from the computer to the SD card.
5. **Ethernet Cable** – To connect the Raspberry Pi to your modem/router.
6. **Internet Modem/Router** with an Ethernet port – For providing a wired internet connection to the Raspberry Pi 3B+.

#### **Software:**
1. [BalenaEtcher](https://www.balena.io/etcher/) – A tool to flash the image file onto the micro SD card.




## Installation
1. **Prepare the Hardware:**
   - Insert the micro SD card into the SD card reader.
   - Connect your Raspberry Pi to the modem/router using the Ethernet cable.

2. **Flash the Image:**
   - Download the image file from the [Releases](https://github.com/username/v2ray-box/releases).
   - Open **BalenaEtcher** on your Windows computer.
   - Select the downloaded image file, choose the SD card, and click **Flash**.

3. **Boot the Device:**
   - Insert the flashed SD card into the Raspberry Pi.
   - Power on the Raspberry Pi and wait for it to boot.

4. **Connect to the v2ray-box:**
   - By default, connect to the WiFi network:
     - **SSID:** `v2ray-box`
     - **Password:** `12345678`
   - Open a web browser and navigate to `http://192.168.2.1:2017`.
   - Use the following credentials to log in:
     - **Username:** `admin`
     - **Password:** `Milad@123`

## Additional Notes
1. **Change WiFi Credentials:**
   - Access the OpenWRT panel at `http://192.168.2.1`.
   - Navigate to the "Wireless" section and update the SSID and WiFi password.

2. **Firewall Configuration:**
   - Ensure that your firewall rules are set up to prevent unauthorized access.

