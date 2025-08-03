# Welcome to the Hackathon of our PhD Cup 2025

## Hardware
- PSOC™ 6 AI Evaluation Kit
- A Type C cable
- A laptop

## Software
Each AI Evaluation Kit has been flashed with our Radar Gesture Recognition Application. We provided an example [code](./main.py) for you to start with. All you need to do now is connect the kit and your laptop with a type C cable using the I/O illustrated below. Then, you should be able to run the example code:
```
## 1. Create a virtual env, the program has been tested with Python 3.7/3.8/3.9/3.10
## 2. Enter your virtual env
## 3. pip install pyserial
## 4. Execute the main.py

## Window 
python main.py COM15 ## Please check your device manager
## Ubuntu
python main.py /dev/ttyACM0 ## Please check your /dev/ttyACM*
## MacOS
python main.py /dev/tty.usbmodem142403 ## Please check your /dev/tty.usbmodem*
```

![](psoc_ai_kit.png)

## Objective
- Make something cool
- Make something helpful 
- Enjoy teamwork!!!
