# Getting-Live-Temprature-and-Humidity-data-Updates-On-Cloud


• First Things First, Connect Esp8266 with DHT11. DHT11 has got 3 pins. Connect Vcc with the 3V pin.
Connect ground with the ground pin os Esp8266. Connect the third pin with one of the data pins of your
choice [D0-D7]

• Go to Thingspeak.com. Create an account. Than create a project. You will get a Read/Write API key.

• Using the DHT libraries get the data from the dht sensor. Note that you might also need the adafruit
sensor library along with it.

• Using the inbuilt wifi adapter connect the ESP8266 with a wifi having a internet connection.

• Thingspeak requires a minimum of 15 seconds of gap between updates. Go to sleep mode while those
15 seconds to conserve battery

• Check on Thingspeak.com, the updates from the sensor being constantly updated.
