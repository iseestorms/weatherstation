# My Weather Observations Weather Station 

This repo if for a Raspberry Pi weather station that uses a Raspberry Pi computer (with an 8MB camera) to take images, crontab scripts overlay information from sensors etc. ImageMagick is used to ovelay data (https://www.imagemagick.org/) before uploading the photo to the web.  Photos can be uploaded to the https://www.myweatherobservations.com site for free and stared in the I See Storms app.

Sensors used are a Light Sensor, BME280 I2C/SPI Temperature, Humidity and Barometric Digital Sensor, ADS1115 ADC 4 Channel 16Bit I2C PGA etc 

Example Camera Output

### Why

To allow uses to share weather data (from sensors) and photos.

* I plan on releasing the code as is for a home only weather station (while under development)
* Then integrating webcam and data submission to https://www.myweatherobservations.com/api/
* Then adding more sensors and making a final hadrware design and PCB. 
* Integrating submitted data with the I See Storms App.

![example camera output](https://www.myweatherobservations.com/fritzing/camera.png)

Sensors and ADC

![bme280 and adc](https://www.myweatherobservations.com/fritzing/sensors.jpg)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

The final version will include a setup.py to download and get the code working in a few lines. The final kit may include a custom Raspberry Pi board with external header conenctors.

### Prerequisites

Things you need.

* 1x $56 AUD Raspberry Pi 2 or Higher. (I have a Raspbery Pi 2 1.1).
* 1x $18 AUD TPi Link 300Mbps Wireless N USB Adapter (TL-WN821N) or other Raspberry Pi Compatible adalter (only needed in Raspberry Pi 1 or 2, 3 has Wifi).
* 1x #39 AUD 8 Mega Pixel Raspberry Pi Camera (3280 x 2464 pixels, 1080p video).
* 1x $7 AUD 30cm Raspberry PI Camera Cable (15Pin FFC FPC Flexible Ribbon Flat).
* 1x $5 ADS1115 4 Channel 16 Bit I2C Analog to Digital Sensor.
* 1x $13 AUD BME280 Temperature Humidity Barometric Pressure Digital Sensor (I2C/SPI).
* 1x $15 Class 10 SD Card.
* 1x Enclosure (as required).
* 2x waterproof metal buttons (one for shutdown and 1 to take an take image).
* 1x $18 Micro USB 2000ma power pack.
* 1x Breadboard +breadboard wires, or protoboard and wires.
* Optional LEDS, Piezo speaker etc.
* etc

Approx total cost: $250

### RaspberryPi Setup

* Format a 16GB Class 10 SD Card with SD Formatter from https://www.sdcard.org/downloads/formatter_4/
* Download the RASPBIAN STRETCH WITH DESKTOP Image with desktop 4.9 o higher from https://www.raspberrypi.org/downloads/raspbian/ 
* Flash the SDCard to the SD Card with Etcher from https://etcher.io/
* Plug the SD Card into the Pi and turn it on.
* Boot the pi and goto the Raspberry start menu then Raspberry > Preferences -> Raspberry Pi Configuration (under the systen tab: Set a password, Set a hostname, Set boot to CLI, Set boot as curret user (pi), Set Wait for Network, Under the Interfaces Tab (Enable)): Camera, SSH, SPI, i2C, Serial, 1-Wire, Under the Performance tab set: 32MB Memory, Under localization set localiza5ion for your region).
* Reboot the Pi (to CLI)

### Wiring Schematic Image (Draft)

Draft Schematic (and Files)

![draft schematic](https://www.myweatherobservations.com/fritzing/alpha-prototype.jpg)

Fritzing File: https://www.myweatherobservations.com/fritzing/weather-station-pi.fzz
Fritzing Parts: https://www.myweatherobservations.com/fritzing/weather-station-pi-parts.zip

### Installing

Todo: A pythoin setup script will be available soon (https://stackoverflow.com/questions/1471994/what-is-setup-py)
 
```
sudo python setup.py install
```

This will download scripts that talk to the analogue sensor, take images ever 2 minutes and upload to the web. 


## MyWeatherObservations.com API information

Todo: ..

## Isee Storms Network information

Todo: ..

## Built With

Bash, Python

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

* **Simon Fearby** - *Initial work* - [ISeeStorms](https://github.com/iseestorms)

See also the list of [contributors](https://github.com/iseestorms?tab=contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

Todo: ..
