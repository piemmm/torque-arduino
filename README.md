# torque-arduino
## Use your own Arduino(etc) based designs in Torque

There is a special protocol in [Torque Pro](https://play.google.com/store/apps/details?id=org.prowl.torque) that lets you connect to devices such as the Arduino, Raspberry pi, and lets you feed the app your own sensor data.   This includes allowing you to tell Torque what sensors are available

The example below uses an Arduino UNO And Micro, a generic bluetooth tx/rx module and a couple of potentiometers as example sensors.  Torque will connect to the arduino, retrieve the list of sensors, then you can view them in the app!

## Advantages

* Gather your own custom sensor data and present it to Torque
* Define your sensor list in the adapter itself, so no messing about adding sensors in the app - they simply appear when connected.
* Build the hardware how you want

## Example Hardware Required

* An Arduino - Uno and Micro boards have both been tested ([Adafruit](https://www.adafruit.com/))
* A 5v tolerant HC-05 or HC-06 bluetooth module ([eBay](http://www.ebay.com/bhp/hc-06))

## Arduino Example Code

Please see the code inside the repository

You can modify this code and customise it to your own requirements - just remember to define the sensors in the sensor list, and torque will then pick up the list of sensors.

