## Adafruit VL6180X ToF Distance Sensor PCB

<a href="http://www.adafruit.com/products/3316"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit VL6180X (VL6180) ToF Distance Sensor. Format is EagleCAD schematic and board layout

For more details, check out the product page at
* https://www.adafruit.com/product/3316

### Description

The VL6180X (sometimes called the VL6180) is a Time of Flight distance sensor like no other you've used! The sensor contains a very tiny laser source, and a matching sensor. The VL6180X can detect the "time of flight", or how long the laser light has taken to bounce back to the sensor. Since it uses a very narrow light source, it is good for determining distance of only the surface directly in front of it.

Unlike sonars that bounce ultrasonic waves, the 'cone' of sensing is very narrow. Unlike IR distance sensors that try to measure the amount of light bounced, the VL6180X is much more precise and doesn't have linearity problems or 'double imaging' where you can't tell if an object is very far or very close.

This is the 'little sister' of the Adafruit VL53L0X ToF sensor, and can handle about 5mm to 100mm of range distance. We've seen up to 150-200mm with good ambient conditions. It also includes a lux sensor. If you need a larger range, check out the VL53L0X which can measure 50 - 1200 mm.

The sensor is small and easy to use in any robotics or interactive project. Since it needs 2.8V power and logic we put the little fellow on a breakout board with a regulator and level shifting. You can use it with any 3-5V power or logic microcontroller with no worries. Each order comes with a small piece of header. Solder the header onto your breakout board with your iron and some solder and wire it up for instant distance-sensing-success!

Communicating to the sensor is done over I2C with some simple commands. Most of the work is handled inside the sensor itself, so its very easy to port our Arduino library to another microcontroller.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
