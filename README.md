# Embedded Systems II: Timers and SPI

## Overview
This project guide provides a brief recap of interfacing with basic board components, including LEDs and pushbuttons, on the STM32 microcontroller. The focus of this practical is to explore the use of timers in embedded systems, which play a crucial role in tasks such as time display, countdowns, and scheduling operations in various appliances like microwaves, ovens, and dishwashers.

## Contents
1. **LEDs and Pushbuttons Recap:** A brief review of interfacing with LEDs and pushbuttons on the STM32 board.
   
2. **Timers Usage:**
   - Creating Delays: Learn how to use timers to create precise delays in your embedded system.
   - Timer Interrupts: Understand how to invoke a timer interrupt to execute code at regular intervals.

3. **Embedded Communications with SPI:**
   - Overview: A summary of the Serial Peripheral Interface (SPI) and its importance in embedded systems.
   - Writing to EEPROM: Utilize SPI to write data to the EEPROM on the UCT STM board.
   - Reading from EEPROM: Retrieve the written data from the EEPROM and store it in a variable.
   - Displaying Patterns: Display the retrieved data on LEDs to create visual patterns.

## Prerequisites
- Basic knowledge of STM32 microcontroller programming.
- Familiarity with LEDs, pushbuttons, and SPI communication.

## How to Use
1. Clone the repository to your local machine.
3. Experiment with the code samples and examples to enhance your understanding of timers and SPI.
4. Explore the resulting LED patterns generated based on the EEPROM data.

## Contributing
If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
