# Design and Implementation of Real-time Operating System on ARM Microcontroller
A Thesis Submitted in Partial Fulfillment of the Requirement for the Degree of Bachelor of Science in Electronic Engineering

Iran University of Science and Technology
Department of Electronic Engineering

# Abstract
Real-Time Operating Systems (RTOS) have become a crucial component in embedded systems, especially in microcontroller-based applications where real-time response is critical. In such systems, the RTOS provides an interface between the hardware and software components, managing system resources, scheduling tasks, and handling interrupts. ARM microcontrollers are widely used in various applications, including automotive, consumer electronics, and industrial control. This project aims to design and implement an RTOS on ARM microcontrollers to improve system performance and reliability.

# Objectives
This project focus on the design and implementation of a simple real-time operating system on an ARM microcontroller, taking into consideration the hardware and software requirements. The RTOS will be responsible for scheduling and executing tasks based on RoundRobin Scheduling Alghorithm; it also shows how to integrate some interrupt like timers with kernel.

# Scope and Limitation
The RTOS is solely developed for ARM Cortex-M series and tested on STM32F3 Discovery Board, the RTOS is not meant to be used in idustrial and sensitive application due to some bugs, remember it's just for demonstration and educational purposes.
Total 3 tasks have been predefined, I recommend not to change it.
The kernel is not compatiable with all third-party libraries, especially Graphical libs like liquad crystal or tft screens, I couldn't find the problem let me know if you figure it out.

# Kernel Features
* RoundRobin Non-preemptive Scheduling Alghorithm
* 
