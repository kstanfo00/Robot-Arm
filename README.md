## Table of Contents
* [Hello_CircuitPython](#Hello_CircuitPython)
* [CircuitPython_Servo](#CircuitPython_Servo)
* [CircuitPython_DistanceSensor](#CircuitPython_DistanceSensor)
* [CircuitPython_LCD](#CircuitPython_LCD)
* [MotorControl](#MotorControl)
---
## Hello_CircuitPython

### Planning
https://docs.google.com/document/d/1FgvvbSDBoRJI06xUQpMpJOgnmd9DKe9SlUZrj4KgW3Q/edit?usp=sharing
### Materials
https://docs.google.com/document/d/1cFgkYVdgJ_m4PIdiOyneVgmMjbTtrUyzixZdNO9I8P0/edit?usp=sharing
### Time Management/Problems Faced
https://docs.google.com/document/d/1CdptpyJqh2Pm-v1EEjkJoalSwdlUqXYwMQoneZT_n74/edit?usp=sharing
### Code
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







### Wiring


### Reflection
This assignment took longer than needed, because of the initial importing of functions into cirucuit python. I also had trouble using the serial monitor as well.

