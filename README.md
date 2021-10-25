# DS18B20_Ambient_Air_Temperature_Sensor

This repository defines a package gathering software elements allowing to measure the air
temperature using a DS18B20 device.

The package is designed following
[this meta-model](https://github.com/HomeMadeBots/Embedded_Software_Meta_Model) and implemented
according to [these C language
patterns](https://github.com/HomeMadeBots/C-language-patterns-for-Embedded-Software-Meta-Model).

## Content

The DS18B20_Ambient_Air_Temperature_Sensor package gathers :
* Component_Types :
  * DS18B20_Sensor

## Overview

![Overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/DS18B20_Ambient_Air_Temperature_Sensor/master/doc/overview.puml)

## DS18B20_Sensor dynamic behavior

![DS18B20_Sensor dynamic behavior](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/DS18B20_Ambient_Air_Temperature_Sensor/master/doc/sd_DS18B20_Sensor.puml)

## Dependencies

![Packages dependencies](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/HomeMadeBots/DS18B20_Ambient_Air_Temperature_Sensor/master/doc/dependencies.puml)

The following repositories shall be retrieved :
* [One_Wire_Interfaces](https://github.com/HomeMadeBots/One_Wire_Interfaces)
* [Physical_Quantities_Interfaces](https://github.com/HomeMadeBots/Physical_Quantities_Interfaces)

## Use

### With the Arduino IDE

This repository shall be clone within the _libraries_ folder of the _Arduino sketchbook folder_.
