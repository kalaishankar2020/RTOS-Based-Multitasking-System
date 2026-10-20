# RTOS-Based Multitasking System

## Overview
An STM32F446RE-based multitasking application developed while learning FreeRTOS through a Udemy course, with additional modifications to implement token functionality. The project explores real-time task scheduling, inter-task communication, UART interrupt handling, software timers, and synchronization using FreeRTOS.

## Key Features
- **Multitasking:** Multiple FreeRTOS tasks for menu handling, command processing, printing, LED control, RTC functionality, and token handling.
- **Token Functionality:** Extended the course-based application with token-related functionality using a dedicated FreeRTOS task and a queue for token data.
- **Queue-Based Communication:** Used FreeRTOS queues to exchange data between application components.
- **UART Communication:** Configured USART2 at 115200 baud for serial communication.
- **Interrupt-Driven UART Reception:** Received user input through UART interrupts and transferred data to a queue.
- **Task Notifications:** Used task notifications to signal the command-processing task from the UART receive callback.
- **Software Timers:** Implemented periodic timers to trigger LED effects.
- **RTC Integration:** Initialized the STM32 Real-Time Clock peripheral.

## Technologies Used
- **Microcontroller:** STM32F446RE
- **RTOS:** FreeRTOS
- **Language:** Embedded C
- **IDE:** STM32CubeIDE
- **Peripheral Library:** STM32 HAL
- **Interfaces:** UART, GPIO, RTC

## Learning Outcomes
- Practiced FreeRTOS task creation and scheduling.
- Implemented queue-based inter-task communication.
- Worked with UART receive interrupts and task notifications.
- Integrated software timers into a multitasking application.
- Extended a course-based project by adding token functionality.


## Project Background
**Course-based project with personal modifications.** Initially implemented while following a Udemy course and subsequently extended with token functionality to gain additional hands-on experience with FreeRTOS.

