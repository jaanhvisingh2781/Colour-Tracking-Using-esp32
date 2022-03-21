# Colour-Tracking-Using-esp32
This project is all about Color Detection & Tracking with ESP32 CAM Module & OpenCV. Thus, we will be detecting any specific colors during live video streaming. Colour detection is necessary to recognize objects, it is also used as a tool in various image editing and drawing apps.
ESP32-CAM FTDI Connection
The board doesn’t have a programmer chip. So In order to program this board, you can use any type of USB-to-TTL Module. There are so many FTDI Module available based on CP2102 or CP2104 Chip or any other chip.

Make a following connection between FTDI Module and ESP32 CAM module.

ESP32 CAM FTDI Module Connection

ESP32-CAM	FTDI Programmer
GND	GND
5V	VCC
U0R	TX
U0T	RX
GPIO0	GND
