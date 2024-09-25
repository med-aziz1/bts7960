# BTS7960 Motor Driver Library

This library provides a simple interface for controlling high-power DC motors using the **BTS7960** motor driver module. It allows users to easily manage motor speed and direction with minimal setup and code.

## Overview

The BTS7960 motor driver is a robust H-Bridge module capable of handling high current, making it suitable for driving DC motors in various applications, such as robotics, CNC machines, and other automation projects. This library abstracts the underlying complexity of controlling the motor, providing straightforward methods to enable outputs, turn the motor in either direction, and stop the motor.

## Installation

To use this library, include the header file in your Arduino sketch

# Usage 

Then create an instance of the BTS7960 with four pins constructor:
```cpp
bts7960 motorDriver(L_EN, R_EN, L_PWM, R_PWM);```
