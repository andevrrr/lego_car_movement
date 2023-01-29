# Lego car

## Description

The car can move in any direction by moving the joystick attached to the board, or via a web page where the user can specify the number of degrees the car will turn, or make it move forward/backward.

The video of how the car moves can be seen on my LinkedIn: https://www.linkedin.com/posts/antonkuch_arduino-arduinoproject-arduinomega-activity-7021528558594338816-fs9_?utm_source=share&utm_medium=member_desktop

## Hardware

For this project, arduino was chosen as the main brain, despite it, the board has many other things attached to it, such as:
- Lcd display (for visualizing some data).
- Joystick (to indicate the direction in which the car will move).
- PWM - Pulse Width Modulation (is a method of reducing the average power delivered by an electrical signal, by effectively chopping it up into discrete parts).
- I2C bus - Inter Integrated Circuit (provides a communication link between Integrated Circuits, in this case, between arduino and the car).
- ESP8266 - a Wi-Fi microchip, with built-in TCP/IP networking software, and microcontroller capability (makes the connection with the software).
- Compass chip (detects the current orientation and direction).
- Motor chassis (move the car).

![alt text](https://github.com/andevrrr/lego_car_movement/blob/main/imagies/logo_car.jpg?raw=true)
![alt text](https://github.com/andevrrr/lego_car_movement/blob/main/imagies/circuit_board.jpg?raw=true)


## Software

The web page sends an Xmlhttprequest to the Wi-Fi module, which is read by the arduino, and then the information goes to the car.

![alt text](https://github.com/andevrrr/lego_car_movement/blob/main/imagies/webpage.png?raw=true)
