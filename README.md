# BMP280

MakeCode BMP280 Digitaler Drucksensor Erweiterung – angepasst für den Calliope mini

Author: shaoziyang  
Date:   2018.Mar  

![](https://raw.githubusercontent.com/microbit-makecode-packages/BMP280/master/icon.png)  
  
![](https://raw.githubusercontent.com/microbit-makecode-packages/BMP280/master/bmp280.jpg)

## Verwendung

Öffne deinen Calliope-mini-MakeCode-Projekt, klicke auf Erweiterungen und füge folgende URL hinzu:

https://github.com/calliope-edu/BMP280  

## I2C Adresse  

- 0x76/0x77  

## API

- function pressure() 
liefert Druck in Pa

- function temperature() 
gibt die Temperatur in Celsius zurück.

- function PowerOn()
schaltet den BMP280 ein.

- function PowerOff() 
geht in den Schlafmodus

- function Address(addr: BMP280_I2C_ADDRESS) 
setzt die I2C-Adresse des BMP280. addr kann sein:
  - BMP280_I2C_ADDRESS.ADDR_0x76
  - BMP280_I2C_ADDRESS.ADDR_0x77

## Demo

![](https://raw.githubusercontent.com/microbit-makecode-packages/BMP280/master/demo.jpg)

## License

MIT

Copyright (c) 2018, microbit/micropython Chinese community  

## Supported targets

* for PXT/calliopemini


[From microbit/micropython Chinese community](http://www.micropython.org.cn)
