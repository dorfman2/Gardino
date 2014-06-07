Gardino
=======

Arduino-based automatic plant watering system


 Gardino 0.6
 6/6/2014
 By Jeffrey Dorfman
 
   The goal of this project is to maintain proper soil moisture for an outdoor plant. It does so by pumping water into the soil
 once a day, and relying on a moisture sensor to test if the soil is already wet (i.e. from rainfall). It will also add an extra
 afternoon watering (heat of the day) if the soil moisture falls below acceptable levels. The ability to water now, or skip 
 next watering, is available via push button on the side of the arduino enclosure.
   Eventually, I would like this project to involve several potted plants. The ideal being is that they require little maintenance,
 other than refilling the reservoir. I would also like to add the option to mist leaves, possibly in cases of extreme heat.
 
 
 HARDWARE:
 
 * Arduino Uno R3
 * Adafruit Motor Shield v1.2
 * Adafruit DS1307 Breakout
 * Pushbutton w/100 resistor
 * 12v power source
 * Elecrow Moisture Sensor (5v)
 * 12v Micro water pump (~1 liter/18seconds)


 LIBRARIES UTILIZED:
 
 * Adafruit Motor shield library - copyright Adafruit Industries LLC, 2009
 
 
 MOISTURE SENSOR:
 
 Value range:
 0 ~300 : dry soil
 300~700 : humid soil
 700~950 : in water
