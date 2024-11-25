# v2ray-box
This software transforms a Raspberry Pi 3B+ into a V2Ray router, providing unrestricted internet via Wi-Fi by using an Ethernet connection for internet input. It allows devices to connect to the Wi-Fi and access the internet without the need for proxy settings on the clients.

This repository does not include any source code. All configurations and setup files are provided as downloadable packages in the [**Releases**](https://github.com/username/v2ray-box/releases) section.

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
     - **SSID:** `v2raybox`
     - **Password:** `Milad@123`
   - Open a web browser and navigate to `http://192.168.2.1:2017`.
   - Use the following credentials to log in:
     - **Username:** `admin`
     - **Password:** `Milad@123`

## Additional Notes
1. **Change WiFi Credentials:**
   - Access the OpenWRT panel at `http://192.168.2.1`.
     - **User:** `root`
     - **Password:** `Milad@123`
   - Navigate to the "Wireless" section and update the SSID and WiFi password.

2. **Firewall Configuration:**
   - Ensure that your firewall rules are set up to prevent unauthorized access.
پ
## Contact
If you have any questions, suggestions, or issues, feel free to reach out:

- **Email:** milad.sm@outlook.com
- **GitHub Issues:** [Create an issue](https://github.com/miladslmz68/v2ray-box/issues)  
- **LinkedIn:** [Milad Salehi Mazandarani](https://linkedin.com/in/milad-salehi-mazandarani)

## Acknowledgements

We would like to express our sincere gratitude to the following projects:

- **v2raya**: For providing the open-source platform that powers this software. v2raya has been instrumental in enabling seamless V2Ray proxy management and client control.  
  Visit their official repository: [**v2raya GitHub**](https://github.com/v2raya)

- **OpenWRT**: For being the backbone of the router management system. OpenWRT provides a flexible and customizable environment, enabling easy configuration and management of network settings.  
  Visit their official repository: [**OpenWRT GitHub**](https://github.com/openwrt)


## Disclaimer
- This project is provided "as is" without any guarantees or warranties.  
- The creator is not responsible for any misuse, damages, or legal issues that may arise from the use of this software.  
- Users are responsible for complying with their local laws and regulations when using this project.  
- For educational purposes only.

## License

This project is released under the [MIT License](LICENSE). You are free to use, modify, and distribute this software in compliance with the terms of the license.

### Third-Party Software Licenses

This project integrates or relies on the following third-party software, each of which is governed by its own license:
- **OpenWRT**: This project uses OpenWRT as the base operating system. OpenWRT is licensed under the [GPLv2 License](https://openwrt.org/license).
- **V2RayA**: This project includes V2RayA for proxy management, which is licensed under the [AGPLv3 License](https://github.com/v2rayA/v2rayA/blob/master/LICENSE).


Please review the respective licenses of these projects for their terms and conditions. By using this project, you agree to comply with the licenses of all included third-party components.



