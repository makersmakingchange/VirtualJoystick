# VirtualJoystick

VirtualJoystick turns your Andoid device into an accessible and user-friendly game controller for your game console or computer. The application uses an Adafruit Feather 32u4 Bluefruit LE board to simulate the functions of a USB HID Joystick. It offers four different controller pad options which gives the users multiple input options to select in order to interact with the host device.

VirtualJoystick supports following controller options:

* XAC Controller Left Pad
* XAC Controller Right Pad
* Controller Direction Pad
* Controller Button Pad

VirtualJoystick can be used to operate Xbox Adaptive Controller through the USB ports.

# Downloads 

These are all the files and documentation associated with the VirtualJoystick project.

 <table style="width:100%">
  <tr>
    <th>Resource</th>
    <th>Version</th>
    <th>Format</th>
    <th>Link</th>
  </tr>
    <tr>
    <td>VirtualJoystick All</td>
    <td>1.0</td>
    <td>ZIP</td>
    <td><a href="https://github.com/milador/VirtualJoystick/archive/master.zip">VirtualJoystick-master.zip</a></td>
  </tr>
  <tr>
    <td>VirtualJoystick Setup Guide</td>
    <td>1.0 (June 2, 2019)</td>
    <td>PDF</td>
    <td><a href="https://github.com/milador/VirtualJoystick/raw/master/VirtualJoystick_Setup_Guide.pdf">VirtualJoystick_Setup_Guide.pdf</a></td>
  </tr>
  <tr>
    <td>VirtualJoystick BOM (csv)</td>
    <td>June 1, 2019</td>
    <td>CSV</td>
    <td><a href="https://github.com/milador/VirtualJoystick/blob/master/Components/VirtualJoystickr_BOM.csv">VirtualJoystickr_BOM.csv</a></td>
  </tr>
  <tr>
    <td>VirtualJoystick Firmware</td>
    <td>1.0</td>
    <td>Ino</td>
    <td><a href="https://github.com/milador/VirtualJoystick/raw/master/Software/VirtualJoystick_Firmware/VirtualJoystick_Firmware.ino">VirtualJoystick_Firmware.ino</a></td>
  </tr>
  <tr>
    <td>VirtualJoystick Application</td>
    <td>1.0</td>
    <td>APK</td>
    <td><a href="https://play.google.com/store/apps/details?id=com.milador.virtualjoystick">VirtualJoystick Application</a></td>
  </tr>
</table> 

# Usage

VirtualJoystick can turn your Android Smartphone or Tablet to a touch base game controller pad. You will need to connect your Adafruit Feather 32u4 Bluefruit LE board to your host device through a USB cable and send the joystick actions from your Android device to host device via bluetooth.


## Components List

  1. Adafruit Feather 32u4 Bluefruit LE X 1 : https://www.adafruit.com/product/2829
  
  2. USB cable - USB A to Micro-B X 1 : https://www.adafruit.com/product/592


## Software Setup Instructions

1. Install the required libraries 
  
1.1. Install Joystick library: https://github.com/MHeironimus/ArduinoJoystickLibrary
  
1.2. Install Adafruit_BluefruitLE_nRF51 library: https://github.com/adafruit/Adafruit_BluefruitLE_nRF51
  
2. Download the firmware 
  
  2.1. VirtualJoystick Firmware : https://github.com/milador/VirtualJoystick/raw/master/Software/VirtualJoystick_Firmware/VirtualJoystick_Firmware.ino
  
  2.2. Bluefruit Configuration : https://github.com/milador/VirtualJoystick/raw/master/Software/VirtualJoystick_Firmware/BluefruitConfig.h
  
  2.3. packetParser File: https://github.com/milador/VirtualJoystick/raw/master/Software/VirtualJoystick_Firmware/packetParser.cpp
  
3. Setup Arduino IDE for your feather board according to the instructions on <a href="https://learn.adafruit.com/adafruit-feather-32u4-bluefruit-le/setup">Adafruit website</a>
  
4. Verify and upload firmware code to your Feather Board

5. Install <a href="https://play.google.com/store/apps/details?id=com.milador.virtualjoystick">VirtualJoystick Android Application</a> in your Android Smartphone or Tablet 

6. Enable Bluetooth in your Android Device

7. Enable Geo Location in your Android Device if you are using the application for the first time. Note: Android SDK 22 and above requires to enable Geolocation to use bluetooth features. You can disable Geolocation permission for the application after the first usage.



## Hardware Setup Instructions

1. Connect Adafruit Feather 32u4 Bluefruit LE to the Micro-B port of USB cable

2. Connect USB A port of USB cable to your host device ( XAC or Computer )

## License 

### MIT License

Copyright (c) 2021 Milador

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<p align="center">
<img align="center" src="https://raw.githubusercontent.com/milador/milador/master/Assets/IMG/mit_license_icon.png" width="50%" height="50%" alt="MIT License"/>
</p>

<!-- ABOUT MMC START -->
## About Makers Making Change
[<img src="https://raw.githubusercontent.com/makersmakingchange/makersmakingchange/main/img/mmc_logo.svg" width="500" alt="Makers Making Change Logo">](https://www.makersmakingchange.com/)

Makers Making Change is a program of [Neil Squire](https://www.neilsquire.ca/), a Canadian non-profit that uses technology, knowledge, and passion to empower people with disabilities.

Makers Making Change leverages the capacity of community based Makers, Disability Professionals and Volunteers to develop and deliver affordable Open Source Assistive Technologies.

 - Website: [www.MakersMakingChange.com](https://www.makersmakingchange.com/)
 - GitHub: [makersmakingchange](https://github.com/makersmakingchange)
 - Bluesky: [@makersmakingchange.bsky.social](https://bsky.app/profile/makersmakingchange.bsky.social)
 - Instagram: [@makersmakingchange](https://www.instagram.com/makersmakingchange)
 - Facebook: [makersmakechange](https://www.facebook.com/makersmakechange)
 - LinkedIn: [Neil Squire Society](https://www.linkedin.com/company/neil-squire-society/)
 - Thingiverse: [makersmakingchange](https://www.thingiverse.com/makersmakingchange/about)
 - Printables: [MakersMakingChange](https://www.printables.com/@MakersMakingChange)

### Contact Us
For technical questions, to get involved, or to share your experience we encourage you to [visit our website](https://www.makersmakingchange.com/) or [contact us](https://www.makersmakingchange.com/s/contact).
<!-- ABOUT MMC END -->
