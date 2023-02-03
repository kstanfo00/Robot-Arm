## Table of Contents
* [Table of Contents](#TableOfContents)
* [Hello_CircuitPython](#Hello_CircuitPython)
* [CircuitPython_Servo](#CircuitPython_Servo)
* [CircuitPython_DistanceSensor](#CircuitPython_DistanceSensor)
* [CircuitPython_LCD](#CircuitPython_LCD)
* [MotorControl](#MotorControl)
---
## Hello_CircuitPython

### Description & Code
This assignment was our intro assignment to circuitpython. Our job was to get the neopixel to blink and change colors. 



```python
import board
import neopixel
import time 

dot = neopixel.NeoPixel(board.NEOPIXEL, 1)
dot.brightness = 0.5 
while True:
    dot.fill((0, 0, 255))
    time.sleep(0.5)
    dot.fill((255, 255, 255))
    time.sleep(0.5)
```


### Evidence


![Untitled_ Sep 27, 2022 3_18 PM (1)](https://user-images.githubusercontent.com/112961430/193047596-eea5442e-cbe6-4e91-b174-e436803c214c.gif)



Image credit goes to [Kaz S](https://github.com/kshinoz98/CircuitPython#Hello_CircuitPython)


### Wiring
There wasn't any wiring required in this assignment.

### Reflection
This assignment took longer than needed, because of the initial importing of functions into cirucuit python. I also had trouble using the serial monitor as well.

