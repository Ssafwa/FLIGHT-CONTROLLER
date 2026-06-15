# FLIGHT-CONTROLLER

# STM32 Flight Controller

A custom flight controller PCB built around an STM32 microcontroller, designed for small to mid-sized multirotor and fixed-wing builds. The board integrates IMU sensing, motor/ESC outputs, RC input, USB connectivity, and status indicators.

.<img width="643" height="515" alt="Screenshot from 2026-06-14 21-12-36" src="https://github.com/user-attachments/assets/d93a26da-49b0-4cde-b586-11f4898e24dc" />

## Softwares

![EasyEDA](https://img.shields.io/badge/EasyEDA-1765AC?style=for-the-badge&logo=easyeda&logoColor=white)
![Brave](https://img.shields.io/badge/Brave-FB542B?style=for-the-badge&logo=brave&logoColor=white)


## Overview

This project started as a way to get a fully custom flight controller working from scratch — designing the schematic, laying out the PCB, and routing everything by hand (including a dedicated ground plane on the bottom layer for noise reduction and cleaner signal integrity).

The board is designed in EasyEDA and is fully open for anyone who wants to build, modify, or learn from it.

## Features

- STM32-based main processor
- Onboard status LEDs and user switches
- Multiple connector headers for peripherals (UART, sensors, motor outputs, etc.)
- USB connectivity for programming/debugging
- Test points broken out for debugging
- Mounting holes for standard frame compatibiliy

Designed in **EasyEDA **.

 <img width="1137" height="795" alt="image" src="https://github.com/user-attachments/assets/0064976a-6f5f-4b6f-98c1-09125874babf" />
this the stm32 main schematics everything is connected with net labels

<img width="1137" height="795" alt="image" src="https://github.com/user-attachments/assets/43050cce-95e8-40d1-95c9-ea9ef9887317" />
and these are the main sensor used in this flight controller 

OTHER FILES AND SCHEMATICS ARE ADDED TO repo root directory view 
