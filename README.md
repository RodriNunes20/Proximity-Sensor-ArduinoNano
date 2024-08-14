# Proximity-Sensor-ArduinoNano
Arduino Nano 33 BLE Sense for proximity detection, made possible by the embedded APDS9960 sensor.

APDS9960 Sensor
The APDS9960 sensor is a multipurpose device that features advanced gesture detection, proximity detection, digital ambient light sense (ALS) and color sense (RGBC).

The sensor's gesture detection utilizes four directional photodiodes to sense reflected infrared (IR) energy, sourced by the integrated LED, to convert physical motion information (i.e. velocity, direction and distance) into digital information.

It features:
 - Four separate diodes sensitive to different directions.
 - Ambient light rejection.
 - Offset compensation.
 - Programmable driver for IR LED current.
 - 32 dataset storage FIFO.
 - Interrupt driven I2C-bus communication.

The APDS9960 library allows us to use the sensor available on the board, to read gestures, color, light intensity and proximity. The library includes some of the following functions:

In order to test out the code, you could begin by stabilizing your board on a standing position in front of you (USB port facing down) and moving an object up and down close to the board. You will see the values on the Serial Monitor changing and changing the color of the RGB LED and the blinking time.

Sometimes errors occur, if the code is not working there are some common issues we can troubleshoot:
 - Missing a bracket or a semicolon
 - Arduino board connected to the wrong port
 - Accidental interruption of cable connection
