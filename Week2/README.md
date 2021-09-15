# Section 11
* MCU Bus Interfaces 
    * I-Bus: Instruction Bus.
    * D-Bus: Data Bus.
    * S-Bus: System Bus.
        * AHB1 (180 MHz)
            * APB1 (45 MHz)
            * APB2 (90 MHz)
        * AHB2 (180 MHz)

    * AHB Bus Matrix


# Section 12
* MCU Clocks
    * Crystal Oscillator (HSE).
    * RC Oscillator (HSI).
    * PLL (Phase Locked Loop) (PLLCLK).

* SYSCLK: main clock of the MCU.


# Section 13
* RCC Engine
* RCC Registers
* Enable the clock to activate the peripherals.
* Select HSE to be the system clock for the Discovery.


# Section 14
* MCU Vector Table.
* Handler Address.
* NVIC, and the IRQ number.


# Section 15
* How the GPIO pin interrupts the processor.
* EXTI Controller Block Diagram.
* GPIOs deliver the interrupt to the NVIC through EXTI lines.
* Clear the PR.

# Section 16
* MCU Device Header File
    * What is a Peripheral.
    * Accessing the registers of a peripheral by linking the peripheral base address to the peripheral structure. 

# Section 17
* Importance of 'volatile' keyword.
* Compiler Optimization Level.
