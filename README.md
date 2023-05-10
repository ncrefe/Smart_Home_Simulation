# Smart_Home_Simulation

•Mediator Design Pattern

•UML Class Diagrams

•UML Sequence Diagrams

•UML State Diagrams

This project involves implementing a Smart Home Simulation in Java, focusing on the concepts of Mediator Design Pattern and UML diagrams. The goal is to create a simulation program for a smart home automation system with the following requirements:

* The system includes temperature, light, and motion sensors that periodically send readings to a mediator object.
* Actuators such as thermostat, light bulb, and door lock receive commands from the mediator and perform corresponding actions.
* A control panel allows the user to set temperature, control lights, and lock/unlock doors, sending commands to the mediator.
* The mediator processes sensor readings and user commands, sending appropriate commands to actuators based on predefined conditions.
* The simulation runs for a specified duration, with sensors sending readings and the control panel sending commands periodically. The current system state (temperature, light status, door status) is output to the console at regular intervals (every 1 second).

Aim is to implement the mediator design pattern to manage communication between components, including sensors, actuators, and the control panel. Writing a Java program that implements the mediator, sensors, actuators, control panel, and simulation logic. The program output the system state to the console for a duration of 20 seconds. The values of sensors and commands for actuators can be randomly decided (except for the automatic thermostat).
