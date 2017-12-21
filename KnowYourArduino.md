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
* Button will be simplest input as it's state is being decided by user not by arduino. 

#### PINs with ~ on digital PINs side ( Analog Output ) 
* In actual these PINs never give output as analog
* Pulse with modulation ( PWM ) technique is being used to give output as analog. 
* Half of time it will be 5V and Half of time it will be 0V. It is too fast and human eyes will see LED as half as brightness.

## Analog Input PINs
* A0-A5 are analog input PINs
* Input value can varry between 0 to 1023. 
* 0 reading means 0V
* 1023 reading means 5V
* Reading x means (x * 5 ) / 1023 V










