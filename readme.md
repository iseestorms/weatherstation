# My Weather Observations Weather Station 

This repo if for a Raspberry Pi weather statuon that uses a Raspberry Pi compyter (with an 8MB camera) and a BME280 I2C/SPI Temperature Humidity Barometric Digital Sensor, ADS1115 ADC 4 Channel 16Bit I2C PGA etc to take photos and sensor data and bash and pythin scripts to overlay the sensor data with ImageMagick (https://www.imagemagick.org/) to ovelay the data before uploading the photo to the web.  Photos can be uploaded to the https://www.myweatherobservations.com site for free and stared in the I See Storms app.

Example Camera Output

![example camera output](https://www.myweatherobservations.com/github/camera.png)

Sensors and ADC

![bme280 and adc](https://www.myweatherobservations.com/github/sensors.jpg)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.
1x $56 AUD Raspberry Pi 2 or Higher. (I have a Raspbery Pi 2 1.1).
1x $18 AUD TPi Link 300Mbps Wireless N USB Adapter (TL-WN821N) or otehr Raspberry Pi Compatible adalter.
1x #39 AUD 8 Mega Pixel Raspberry Pi Camera (3280 x 2464 pixels or 1080p video).
1x $7 AUD 30cm Raspberry PI Camera Cable (15Pin FFC FPC Flexible Ribbon Flat).
1x $5 ADS1115 4 Channel 16 Bit I2C Analog to Digital Sensor.
1x $13 AUD BME280 Temperature Humidity Barometric Pressure Digital Sensor (I2C/SPI).
1x $15 Class 10 SD Card.
1x Enclosure.
2x waterproof metal buttons (one for shutdown and 1 to take an take image).
1x $18 Micro USB 2000ma power pack.
Breadboard +breadboard wires, or protoboard and wires.
Optional LEDS, Piezo speaker etc.

Approx total cost: $250

### Why

Todo...

### Roadmap

I plan on releasing the code as is. 
Then integrating submission to https://www.myweatherobservations.com via API from the weathervstation.
Building in more sensors. 
Integrating with the I See Storms App.

### Installing

A pythoin setp script will be available soon (https://stackoverflow.com/questions/1471994/what-is-setup-py)
 
```
sudo python setup.py install
```

This will downlaod scripts that talk to the alalog sensor, tale imagfes ever 2 minutes and upload to the web. 

## Hardware Schematics

todo..


## Deployment

Add additional notes about how to deploy this on a live system soon.

## MyWeatherObservations.com API information

todo..

## Isee Storms Network information

todo..

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

todo..
