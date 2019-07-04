# Class 0: Introduction to Arduino and programming
## 0. Generally in programming we count starting from 0 instead of from 1
## 1. What is Arduino?
- Arduinos come in many different types. The type of Arduino we will be using is called an Arduino Nano.
- The brains of the Arduino is called the microprocessor. In the Arduino Uno and Nano this is the ATmega328P.
- The rest of the Arduino is called the PCB (printed circuit board) and is just how you connect things to the microprocessor, which actually does the work.
- Arduino also comes with its own IDE (integrated development environment). This makes things easier in exchange for not having as much control.
- Arduino is a good starting point for learning to program electronics due to its widespread adoption and wealth of documentation online
- Arduino is Open-source meaning they release the schematics and code for everything so you could design your own Arduino board if you wanted
## 2. Download [Arduino IDE](https://www.arduino.cc/en/Main/Software), set the right programmer/board/processor/port
- You can program the Arduino with a USB cable 
- Click the link above and download the file, extract the zip file, launch the IDE
- Under tools in the IDE:
  - Set the board as "Arduino Nano"
  - Set the processor as "ATmega328P (Old Bootloader)"
  - Set the programmer as "AVRISP mkll"
  - Set the port to whatever shows up
## 3. The Arduino IDE is based on the C/C++ programming languages
- You'll need to follow specific syntax or your code will throw errors and not compile
- Some examples are: 
  - You must put strings in double quotes
  - You must add a semicolon after you write specific lines of code (like a period at the end of a sentence)
