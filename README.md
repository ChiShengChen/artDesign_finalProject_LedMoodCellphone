# artDesign_finalProject_LedMoodCellphone


This the final project for class Contemporary Art and Cross-Disciplinary Design in NCTU.

## Concept
This work we try to expound technology indifference with the leds and cellphone control. In other words, I wrote a android app to get the z-axis data from gyroscope sensor in the cellphone, when someone pick up the phone, which let the z-axis velocity > 1, the phone will sent a string "rain" through bluetooth to the device and let it blink the blue light. 


![image](https://github.com/ChiShengChen/artDesign_finalProject_LedMoodCellphone/blob/master/%E8%9E%A2%E5%B9%95%E5%BF%AB%E7%85%A7%202019-06-22%20%E4%B8%8B%E5%8D%886.06.46.png)

On the other hand, when someone put down their cellphone, which let the z-axis velocity < 1, the phone will sent a string "sun" through bluetooth to the device and let it blink the red light. 
![image](https://github.com/ChiShengChen/artDesign_finalProject_LedMoodCellphone/blob/master/%E8%9E%A2%E5%B9%95%E5%BF%AB%E7%85%A7%202019-06-22%20%E4%B8%8B%E5%8D%886.05.57.png)

## Circuit bom list
- Any Arduino board * 1 (I used UNO in this project).
- HC-05 bluetooth board * 1.
- 1K resistor * 1.
- 2K resistor * 1.
- ws2812b leds depends on your need.
- Breadbord * 1.
- Some wire for connecting the components.

## Wring
![image](https://github.com/ChiShengChen/artDesign_finalProject_LedMoodCellphone/blob/master/F1OOYJNIR413HTY.jpg)
(The photo is copy from https://reurl.cc/yN6XM ）
