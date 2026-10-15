# ADC_PollingandIT_Mode_STM32

## Overview

This project demonstrates two methods of reading ADC conversion results on the STM32 Nucleo-F446RE development board using STM32 HAL and STM32CubeIDE:

- ADC Polling Mode (ADC_Polling)

- ADC Interrupt Mode (ADC_IT)

Both implementations measure the STM32's internal temperature sensor, transmit the results to a PC terminal through UART2.

## Hardware

- STM32 Nucleo-F446RE development board
- USB connection to PC

## Software and Tools

- STM32CubeIDE
- STM32CubeMX
- STM32 HAL
- C programming language

## Features

- ADC configuration for internal temperature sensor measurement
- Demonstrates ADC data acquisition using polling mode (ADC_Polling.c)
- Demonstrates ADC data acquisition using interrupt mode (ADC_ITmode.c)
- UART communication between the STM32 microcontroller and a PC terminal

## Project Structure

- `Core/Inc/` — application header files
- `Core/Src/` — application source files
- `Drivers/` — STM32 HAL and CMSIS dependencies
- `.ioc` — STM32CubeMX configuration file
