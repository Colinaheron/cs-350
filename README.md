# cs-350
repo for the cs350 class at SNHU
The project involved creating a state machine to blink LEDs in SOS and OK Morse code sequences and to switch between these sequences based on button presses. The primary goal was to manage the timing of LED blinks accurately and to ensure the message change only occurred after the current message completed.

Problem Solved
Implementing a state machine to handle precise timing for Morse code sequences.
Using interrupts and timers to manage asynchronous events and ensure real-time responsiveness.
Detecting and handling button presses to toggle between messages without disrupting the current sequence.
Key Achievements
State Machine Implementation: Successfully implemented a state machine to handle Morse code blinking with precise timing using timers and GPIOs.
Interrupt Handling: Effectively used interrupts to detect button presses and toggle messages, ensuring the system responded to user inputs.
I2C Integration: Integrated I2C to detect and communicate with temperature sensors, demonstrating the ability to manage peripheral communication.
Areas for Improvement
Code Documentation: Adding more comments and detailed documentation could improve code clarity and maintenance.
Error Handling: Implementing more robust error handling for hardware failures or unexpected states could make the system more resilient.
Modular Design: Breaking down the code into more modular functions could enhance readability and reusability.
Tools and Resources Added to Support Network
Texas Instruments (TI) Driver Libraries: Utilized TI’s driver libraries for GPIO, Timer, I2C, and UART, providing a robust foundation for peripheral management.
State Machine Design Patterns: Leveraged state machine design patterns to handle complex sequences and transitions efficiently.
Embedded System Development Tools: Gained experience with tools like CCS (Code Composer Studio) for embedded development and debugging.
Transferable Skills
State Machine Design: The ability to design and implement state machines is crucial for managing complex sequences and events in embedded systems.
Interrupt and Timer Management: Skills in configuring and using interrupts and timers are applicable in various real-time system applications.
Peripheral Communication: Experience with I2C and UART communication will be useful in projects involving sensor integration and data transmission.
Embedded C Programming: Enhanced proficiency in embedded C programming, crucial for firmware development.
Maintainability, Readability, and Adaptability
Structured Code: Organized the code with clear function definitions and consistent naming conventions to enhance readability.
Modular Design: Segregated different functionalities (e.g., timer callback, I2C initialization) into distinct functions to improve modularity.
Detailed Comments: Added comments to explain the purpose of each function and the logic within complex sections, aiding future developers in understanding the code.
Parameterization: Used defined constants and parameters (e.g., timing durations) to make the code easily adjustable for different requirements.
Summary
This project demonstrated the integration of hardware interrupts, timers, and peripheral communication within an embedded system. The skills and methodologies developed, such as state machine design and interrupt management, are highly transferable to other projects, enhancing both technical capabilities and project maintainability.
