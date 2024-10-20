# artcar-ultrasonic-dist-Arduino
Arduino ultrasonic distance - three sensors, can be front/back-facing and has temp/humidity correction

** Refactored to Raspberry Pi Pico 2 **
* https://github.com/bradcar/artcar-ultrasonic-dist-rp2

My work is based on UPIR's GREAT work: https://github.com/upiir/arduino_parking_sensor created by UPIR, 2022
* UPIR youtube channel: https://www.youtube.com/upir_upir
* UPIR youtube full video: https://youtu.be/gg08H-6Z1Lo
* UPIR Github: https://github.com/upiir/arduino_parking_sensor
* UPIR full simulation https://wokwi.com/projects/348388602879672914

To see my Art Car, it's the 5th image down in https://en.wikipedia.org/wiki/Art_car  , the one with the caption: "Unofficial BMW Art Car by Tom Cramer..."

Other Useful sites:
* u8g documentation: https://github.com/olikraus/u8glib/wiki/userreference
  * u8g fonts (fonts available for u8g library): https://nodemcu-build.com/u8g-fonts.php
* image2cpp (convert images into C code): https://javl.github.io/image2cpp/
* waterproof sensors: https://www.youtube.com/watch?v=h6321UBATps

Note: Temp & humidity correction for the speed of sound
* speed of sound going from 0C to 30C goes from 331.48 m/s to 351.24 m/s (~ 6%)
* speed of sound at 30C goes with a humidity of 0% to 90% goes from 349.38 m/s to 351.24 m/s (~ 0.53%)
* ...humidity effect is negligible, but I had a dht22 which does both, so why not :)
