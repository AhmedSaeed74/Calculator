# Dynamic Calculator Application

Welcome to the Dynamic Calculator! Experience limitless calculations with flexible input and configurable LCD and keypad drivers.

Features
-Dynamic Memory Allocation: The calculator employs linked lists and dynamic memory allocation, allowing users to conveniently input any number of operands and operators. Inserting and deleting numbers and operators are streamlined for ease of use.
-Flexible LCD Configuration: The LCD driver can be configured to operate in either 4-bit mode or 8-bit mode, adapting to different hardware setups and requirements.
-Adaptable Keypad Handling: The keypad driver supports polling and interrupt-based modes, offering flexibility in capturing and processing user input.

Layers
-MCAL Layer (Microcontroller Abstraction Layer)
 DIO Driver: This driver handles digital input and output operations, enabling interaction with external devices and components.
 External Interrupts Driver: Responsible for managing external interrupts, ensuring responsive interactions with peripherals like the keypad.

-HAL Layer (Hardware Abstraction Layer)
 LCD Driver: This driver controls the LCD display module, offering the choice between 4-bit and 8-bit communication modes based on the hardware configuration.
 Keypad Driver: The keypad driver provides functionality to read and interpret keypad input, allowing users to interact with the calculator application.
 
-Application Layer
 The Application Layer orchestrates the calculation of arithmetic operations, including addition, subtraction, multiplication, and division. Upon entering the "=" sign, the result of the calculation is displayed on the LCD screen.

Getting Started
To begin using the Dynamic Calculator Application, follow these steps:
1-Configure the MCAL and HAL drivers according to your microcontroller specifications.
2-Configure the desired LCD mode (4-bit or 8-bit) by modifying the appropriate settings in the LCD driver.
3-Choose between polling or interrupt-based input for the keypad driver, based on your application's requirements.
4-Utilize the dynamic memory allocation features of the calculator to input operands and operators as needed.
5-Interface with the calculator through the keypad, perform arithmetic operations, and observe the results on the LCD display.

link for a video showing how the calculator passes the test cases.
https://drive.google.com/file/d/1m8l5gqXNkB-4jlqSaLyHLjCkxiX1LdFt/view?usp=sharing
