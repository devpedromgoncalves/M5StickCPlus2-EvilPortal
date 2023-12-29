# M5StickC Plus 2 Evil Portal

This project implements a captive portal on an M5StickC Plus 2 device (in Portuguese language). 

It creates a fake WiFi access point and captures credentials entered by any user attempting to connect.

This project was created based on https://github.com/DanyBit/M5Stick-Captive-Portal.

## Features

- Fake WiFi access point with a custom login page.
- User credential capture (email and password).
- Victim count display on the M5StickC Plus 2 screen.
- Web interface for viewing captured credentials.

## How to Use

1. Clone the repository to your local development environment.
2. Open the project with the Arduino IDE or any editor of your choice.
3. Compile and upload the code to your M5StickC Plus 2.
4. After uploading, the device will create a WiFi access point.
5. Connect to the WiFi created by the device to view the login page.

## Configuration

The `Portal.ino` file contains the main source code. Changes can be made to customize the access point SSID, login page, and other settings.

## Disclaimer

This project was created for educational and demonstration purposes. It is not recommended, nor should it be used for malicious or illegal activities.

## Credits

Developed by Pedro Gonçalves
