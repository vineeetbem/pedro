# pedro

A fully custom FPV drone flight controller designed from scratch, from component selection and schematic design to PCB layout and routing.

The flight controller is built around the **STM32H743** microcontroller and includes high speed IMU sensors, barometric altitude sensing, external flash and MicroSD storage, multiple UART and SPI interfaces, CAN communication, USB connectivity, battery voltage monitoring, and dedicated power regulation.

The project was designed in **KiCad**, with the focus on creating a compact and feature rich flight controller suitable for FPV and future custom flight control firmware development.

## Current Status

The complete schematic has been designed and the PCB layout, component placement, routing, board outline, and silkscreen have been completed. The design is currently at the final review and manufacturing preparation stage.

## Main Features

STM32H743 based flight controller

Dual IMU setup for motion sensing

Barometric altitude sensor

External SPI flash and MicroSD storage

Multiple UART, SPI and I2C interfaces

Dual CAN interfaces

USB connectivity

Battery voltage monitoring

5V, 12V and 3.3V regulated power rails

SWD debugging interface

Status LEDs and buzzer

Compact PCB with four mounting points

## Project Goal

The goal of this project is to understand and develop a flight controller at the hardware level instead of relying entirely on an existing commercial board. The project covers the complete process from reading datasheets and selecting peripherals to schematic design, PCB layout, routing, and eventually hardware testing.
