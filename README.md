Telegram Bot-Controlled ESP32 Camera

Overview

This project utilizes the ESP32-CAM module and the Telegram Bot API to capture images and send them directly to a Telegram chat. Users can remotely trigger the ESP32-CAM via a Telegram bot command and receive real-time images.

Features

Remotely capture images using a Telegram bot.

Send captured images directly to a specified Telegram chat.

Lightweight and efficient communication using Telegram's API.

Supports Wi-Fi connectivity for remote access.

Hardware Requirements

ESP32-CAM module

FTDI Programmer (for flashing firmware)

Jumper wires

A stable Wi-Fi connection

Software Requirements

Arduino IDE

ESP32 Board Package installed in Arduino IDE

Telegram Bot API Token

Required Arduino libraries:

WiFi.h

ESP32Servo.h

UniversalTelegramBot.h

ArduinoJson.h

Setup Instructions

Create a Telegram Bot:

Open Telegram and search for BotFather.

Use /newbot command to create a new bot.

Copy the provided API token.

Flash ESP32-CAM with Firmware:

Install required libraries in Arduino IDE.

Configure Wi-Fi credentials and Telegram bot token in the code.

Upload the code to the ESP32-CAM.

Run the Project:

Power up the ESP32-CAM.

Send the /photo command to your Telegram bot.

Receive the captured image in the chat.

Usage Commands

Command

Description

/start

Start the bot and receive a welcome message.

/photo

Capture an image and send it to the Telegram chat.

/status

Get the current status of the ESP32-CAM.

Troubleshooting

If images fail to send, ensure Wi-Fi credentials are correct.

Check for correct wiring and power supply to ESP32-CAM.

If the bot doesn't respond, verify that the Telegram API token is correct.

Future Enhancements

Add video streaming support.

Implement AI-based object detection in captured images.

Improve low-light image quality.

License

This project is open-source and licensed under the MIT License.

Author

Developed by SASHANK

Feel free to contribute, report issues, or suggest improvements!

