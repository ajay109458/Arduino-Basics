# Know Your Arduino

## Getting to know Arduino Uno 

#### Microcontroller 
* A digital input/output pin allows the microcontroller to interact with the world around it. 
* Using a digital input/output pin, the microcontroller can read or change the state of an external device, like a button or a light. 
* GPIO - General purpose Input/Output pin. 
* Microcontroller don't have any operating system. 
* You can replace your 328 microcontroller on your arduino board. 

#### Atmel ATMega16U2
* Implements the USB serial interface. 
* It controls communication between your computer and microcontroller via USB port. 

#### PINs
* Using these pins you connect arduino to outer world. 
* In order to connect - use jumper wires. 
* Another way to connect is using shield.
* A0-A6 - Analog inputs
* 0 - 13 - Digital inputs
* SDA - Communication inputs

#### Power
* Power can be provided using USB or external power supply input. 
* 7 - 12V = Recommended input voltage. Try to use powersupply ~9V. 
* Arduino has a voltage regulator. 

#### ICSP 
* In-Circuit serial Programming

#### Clock
* Clock on board has been calibrated to beat at 16 million times per second. (16 MHz) 

#### Capacitor
* Clean extra voltage or fluctuation in power supply as microcontroller need exact 5V. 

## Using the digital Output PINs
* 14 Digitals pins are numbered from 0 to 13
* PINs are there to read/write digital input. 
* Microcontroler 1(HIGH) means 3.5-5V 
* Microcontroller 0(LOW) means 0-3V

#### Excecise 
* Connect a LED to arduino.

#### LED
* Smaller leg is -ve leg and need to connect to ground. 
* Larger leg is +ve leg and you need to connect it any PIN from 0-13. 
* Always connect a register in circuit. 
* HIGH to PIN will turn on the LED
* LOW to PIN will turn off the LED. 

## Using the digital Input PINs







