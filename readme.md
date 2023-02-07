# STM32F407 Projects
<p>This repository contains projects and learning I have done using an STM32 microcontroller, namely the STM32F407 Discovery board.</p>

## Projects so far

### hello-stmdiscovery
<p>As my very first foray into learning embedded programming with STM32, this project is very small but was nonetheless rewarding. This project focused on learning how to use the GPIOs, mainly the LED pins. This project also taught me about using interrupts and using the USB COM port for serial communication between the connected PC and the board. </p>
<p>Two of the LEDs are programmed to blink periodically in a pattern. One of the LEDs can be turned on and off using the board's user button. Finally, an LED can be toggled using the terminal when the board's micro-USB is connected. A string, sent from the board to the terminal, prompts the user to input 1 or 0, which toggle the LED on and off respectively.</p>