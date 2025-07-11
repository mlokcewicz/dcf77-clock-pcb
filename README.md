# dcf77-clock-pcb

**DCF77-controlled** radio clock PCB based on the **ATmega88** microcontroller, **MAS6181B** AM receiver, and **DS1307** RTC.

![dcf77_clock_assembled](./dcf77_clock_assembled.JPG)

**Capabilities:**
* Time and date display
* Alarm handling
* Manual date and time setting
* Automatic periodic synchronization with the DCF77 signal
* Time synchronization status display
* Time zone configuration
* DCF77 signal parameters preview during synchronization
* Time and date data available over the serial port
* Time and date retention powered by a CR2032 battery
  
**Hardware:**
* ATmega88 MCU
* MAS6181B DCF77 receiver
* DS1307 RTC + CR2032
* 2x16 HD44760 LCD
* Rotary Encoder + Button + LED + Buzzer

**Firmware:**
* C11
* Custom MCU peripheral and external circuit drivers

## Tools
* Autodesk EAGLE v9.6.2

## External links
* Firmware repository: https://github.com/mlokcewicz/dcf77-clock

## License
This project is licensed under the CERN Open Hardware Licence Version 2 - Permissive - see the [LICENSE](./LICENSE) file for details.
