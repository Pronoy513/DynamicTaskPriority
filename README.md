# DynamicTaskPriority

This project is created for working on https://wokwi.com/, and uses its  hardware & libraries for running.

The goal of the project is to create a reliable and efficient system that can change the priority order of its tasks in real
time, allowing the user to take real-time factors into consideration and manually reorder
the priority of tasks to ensure that the best course of action is taken in the current scenario.

This uses an ESP32 processor to run the program, and additional hardware, i.e., keypad, breadboard, and LED, all of which provided by Wokwi Simulator.
FreeRTOS, a very popular real-time operating system and its libraries, manage the lower level components on the ESP32, and is extensively used
throughout the project for task handling.

The complete implementation of the project can be found through the link: https://wokwi.com/projects/365685910771785729
