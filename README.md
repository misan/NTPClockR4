# NTPClockR4
A modified example to include the LCD matrix display of the IP address and the time for the Arduino UNO R4 WiFi board.

It is based on the built-in example for UDP NTP.

[![Sample video](https://img.youtube.com/vi/qsTvNGd3lPs/0.jpg)](https://www.youtube.com/watch?v=qsTvNGd3lPs&ab_channel=MiguelS%C3%A1nchez)

Make sure you setup your WiFi data on arduino_secrets.h file.

Make sure you select the right value to be added to the received time so the printed time matches your time zone: https://github.com/misan/NTPClockR4/blob/29b24a03f2e1c9daf76ddc6ff8aac4c7c6cbb149/WiFiUdpNtpClient_LED/WiFiUdpNtpClient_LED.ino#L144

