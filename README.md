
# CO2 Monitor using Raspberry Pi Pico and MH-Z19B

This project utilizes a Raspberry Pi Pico and classic 0.96" OLED to read and display current CO2 levels. There are similar projects using Arduino or ESP32, but I have not seen someone using a Pico yet. Its cheaper, smaller, and less power hungry which is why it was chosen. I did not need wireless capabilities in my case, however using a Pico W you could easily impliment this. 

Programmed in Micropython with ssd1306 library for the OLED.

Features include:

- Warm up time with progress bar
- PPM Display with bar graph
- Interpretation of PPM ranging from Mild to Hazard
- Software PPM calibration with instructions
- Line indicating level at which cognitive ability begins to become impared (according to 2016 Harvard study)

## Demo
![IMG_9293](https://github.com/SkelaKing/Pico-CO2/assets/104640817/ba601b1c-f63b-4249-a12c-aa14c3a2b810)
![image](https://github.com/SkelaKing/Pico-CO2/assets/104640817/0eaa53b9-7859-4819-a5e8-ba08476ae5f4)



## Documentation

[Harvard Study on Cognitive Functions at Different CO2 Levels](https://dash.harvard.edu/bitstream/handle/1/27662232/4892924.pdf?sequence=1)

[MH-Z19B Manual](https://www.winsen-sensor.com/d/files/infrared-gas-sensor/ndir-co2-sensor/mh-z19b-co2-manual(ver1_6).pdf)

[Thingiverse link for case](https://www.thingiverse.com/skelakinghd/designs)
