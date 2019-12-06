# DIY Home Assistant Cat Feeder - Using ESPHome and Home Assistant. WORK IN PROGRESS!
This catfeeder features quite a lot of tech! Besides its main funtion of a feeder itself, it also has:<br>
An ultrasonic sensor to tell us when the feeder is low^.<br>
And ESPHome to tie it into your Home Automation system!<br>
And it is really cheap!

# Footnotes:

Thanks for checking this out! Here is what my prototype cat feeder looks like:
<a href="https://imgur.com/hxLt5IY"><img src="https://i.imgur.com/hxLt5IYh.jpg" title="source: imgur.com" /></a>

# Here's what you need for hardware:
-  1x NodeMCU v3 ESP8266 (I use an Lolin NodeMCU, but any NodeMCU or WeMos D1/ D1 Mini will work) https://ebay.us/EqwFiP ~5€
-  1x Servo Motor Continuous SM-S4303R: https://amzn.to/2YpssPv ~10€
-  1x Ultrasonic Module HC-SR04 Distance Transducer Sensor For Arduino Robot  https://ebay.us/ei9Pcy ~2€
-  1x Whatever Smartphone Charger https://amzn.to/2OTBqS0 ~15€
-  1x takestop Dry-Food Dispenser https://amzn.to/2YlzHs1 ~15€
-  Various header wires (male-male, male-female, female-female)
-  A USB-A to Micro USB cable.
-  Dremel or drill.

Around 35€ if you a have a spare charger at home. Even cheaper if you get bulk sensors and Lolins or WeMos from Bangood or Aliexpress. The most expensive item is the Dispenser and usually they arren't very well made... But if we got the mechanics and automations, a cilinder and a D shape rotary axis is really easy to make in 3d ;)

# Todo List:
* Some scale or sensor to detect the bowl placed below, to stop the automation if not or if it full.
* Some 3d printing:
  * Lolin case: https://www.thingiverse.com/thing:2850128
  * Servo mount: https://www.thingiverse.com/thing:3269637
# Building it!
Sorry, I had no pictures of the build process, but here's what I can give you:
* Compile the code inside EspHome and download the binary to install it with EspHome Flasher.
* Fit the ultrasonic sensor below the lid with screws, some hot glue, whatever fits for you.
* With a drill or dremel, drill a passthrough to connect the ultrasonic sensor to the Lolin. I use four pins, to make it detachable.
* Screw the servo motor to the rotary handle.
* Connect the pins as set below.
* Connect your MicroUSB 
* Create the package for Home Assistant and restart the server.
<a href="https://imgur.com/FNGvack"><img src="https://i.imgur.com/FNGvack.png" title="source: imgur.com" /></a>
