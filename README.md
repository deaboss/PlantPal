# Plant Pal
All code written by Ethan Dea<br>
Housing Design by Etienne de Raynal, Noah Dunsmore, and Ethan Dea<br>
Plant Pal is an esp32 Based Smart Plant Pot that can handle all aspects of plant care.<br>

## Features

The device features a soil moisture meter, water pump, LED grow lights, and an OLED screen. All of these devices work in unison to take care of your plant. Plant Pal is capable of taking care of many different types of plants.

### Setup
During setup users will choose between Auto and Custom modes<br>
Auto provides a much more streamlined setup process while custom allows users to set each function individually. 
### Auto Mode
User Selects between 5 plant types<br>
-Succulent<br>
-Broad Leaf<br>
-Fern<br>
-Herb<br>
-Seedlings<br>
All settings will be automatically set for the user.

### Custom Mode
Users will walk through setting up each function individually.<br>
1. Hours of sun<br>
> User sets how many hours of artificial light the plant will get per day<br>
2. Soil Humidity Trigger Level<br>
> User sets the humidity that will trigger watering whenever a soil check happens
> If the measured soil humidity is lower than the trigger value the PlantPal will begin watering
3. Days between watering<br>
> This is how often PlantPal will check to see if the soil humidity is lower than the trigger value.
4. Water Ammount<br>
>User sets how much water will be dispensed in mL if PlantPal determines low soil humidity.

### Daily Use
When in use, PlantPal will display current soil humidity and light on/off time.


## Component List

-[Small Water Pump]([https://pip.pypa.io/en/stable/](https://ae01.alicdn.com/kf/S13d096682cce42adb18643b46f7653ebq.jpg_640x640Q90.jpg_.webp)https://ae01.alicdn.com/kf/S13d096682cce42adb18643b46f7653ebq.jpg_640x640Q90.jpg_.webp)<br>
-USB C Breakout Board<br>
-LED Grow Lights<br>
-Monochrome OLED Display (128X32)<br>
-2 Buttons<br>
-2 Transistors (for LEDs and water pump)<be>
-Soil Humidity Sensor<br>

## Images
![Images2](https://github.com/deaboss/PlantPal/blob/main/IMG_9289.JPG)
![Image1](https://github.com/deaboss/PlantPal/blob/main/20230605_064401524_iOS.jpg)
