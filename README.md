# FlipDot-ws2811
Control 1x7 flipdots with ws2811, esp32 and Adafruit_NeoPixel 


Flipping the dots is possible up to 30 times per second
Video: https://youtu.be/RNscDvGn9HI

falstad circuit simulation  https://tinyurl.com/ybub3474

No use of shift registers but controlling each dot seperatly. Original idea from https://pierremuth.wordpress.com/2021/02/17/flipping-dots-fast/ 
I utilise the commonly, cheap and easy to control ws2811 ic to control the dots. So lots of arduino libraries are available.
In my example I use the Adafruit_NeoPixel library.
