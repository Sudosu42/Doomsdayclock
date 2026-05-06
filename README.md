# Doomsdayclock
The Doomsday clock is a physical representation of the "Doomsday Clock" from the Bulliten of Atomic Scientists. It also serves as a handy clock that ticks down each minute to midnight in your local area! 
                                               - Required Hardware -
• 1x ESP32-S3-Zero
• 1x 0.96" 128x64 IIC OLED Display (4-Pin)
• 1x Momentary Micro Button, dealers choice
• 3D Printer (The case itself or a creation kit can be found on my website!)

-------------------------------------------------------------------------------------------------------------------------------
Function

The clock has 2 modes: 1. Doomsday Clock. In this mode the mini LCD will display how long it is to midnight acording to the Bulletin of Atomic Scientists. 2. Midnight Countdown, In this mode the mini LCD will display how long until midnight in your area in minutes and seconds. 
-------------------------------------------------------------------------------------------------------------------------------
Instructions

1. Download and extract the code for the ESP32-S3-Zero and add them to the Arduino IDE. The code requires some libraries, theyr're listed at the top of the script.
2. Where you see "YOUR_BSSID_HERE" and "PASSWORD" in the script, replace with your wifi information. (Keep the qoutation marks).
3. Verify the script and then upload it to the ESP32-S3-Zero. If you run into busy errors or any errors connection to the ESP32, hold down the boot button for the duration of the flash.
4. Print the 3 case parts and wire the electronics following the wiring diagrams below.

LCD

| OLED Pin | ESP32-S3-Zero |
| -------- | ------------- |
| VCC      | 3.3V          |
| GND      | GND           |
| SDA      | GPIO 8        |
| SCL      | GPIO 9        |
 
Button

| Button Pin | ESP32-S3-Zero |
| ---------- | ------------- |
| One side   | GPIO 10       |
| Other side | GND           |
