# DIY Multi-Sensor Cat Feeder - Using ESPHome, Home Assistant, and Node Red
This catfeeder features quite a lot of tech! Besides its main funtion of a feeder itself, it also has an ultrasonic sensor to tell us when the feeder is low*, a DHT11** to tell us temperature and humidity, an HC-SR505*** for motion detection, and tie it into your Home Automation system!
<b> Fotnotes: </b>
* Te feeder sends an HTML5 Notify alert to my phone, for HTML5 Notifications, see https://www.home-assistant.io/components/html5/
** A DHT11 sensor isn't as accurate as the DHT22, however, the DHT11 is cheaper. I purchased 5 of them at once to sweeten the deal.
*** The HC-SR505 I got also in bulk as I thought they'd work pretty well. They do work well for this application, but they cannot be close to your ESP8266 device, else it will throw false positives. I have mine about 8 inches from my ESP8266 device and the flase positives are nought.

Thanks for checking this out! Here is what my prototype cat feeder looks like:

# Here's what you need for hardware:
-  1x ESP8266 (I use an Amica NodeMCU, but any NodeMCU or WeMos D1/ D1 Mini will work) <br>
-  1x Servo Motor: https://www.amazon.com/dp/B076CNKQX4/
-  1x DHT11 Temperature and Relative Humidity Sensor Module https://ebay.us/O6WnL4 ^
-  1x HC-SR501 PIR IR Passive Infrared Motion Detector Sensor Module / Arduino HCSR501  https://ebay.us/zmt1I4 ^
-  1x Ultrasonic Module HC-SR04 Distance Transducer Sensor For Arduino Robot  https://ebay.us/ei9Pcy ^ 
-  1x LM2596S DC-DC 3A Buck Adjustable Step-down Power Supply Converter Module https://ebay.us/D48M8h ^
-  1x 3PCS Micro Lockless Momentary On/Off Push Button 12V 5A Switch Tact Assortment  https://ebay.us/NRSOpU ^
-  1x 3X Mini 400 Point Solderless Prototype PCB Breadboard Protoboards https://ebay.us/5bkxw9 ^
-  1x AC100-240V To DC 12V 3A US Power Supply Adapter Transformer https://ebay.us/yqAJVE
-  1x Zevro KCH-06138 13-Ounce Dry-Food Dispenser https://www.amazon.com/gp/product/B0009MGQUC/
-  1x 6"x6"x1/2" Piece of wood of choice
-  1x 6"x18"x1/2" Piece of wood of choice
-  2x Drywall screws
