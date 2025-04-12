# dcf77-clock-pcb

DCF77 controlled radio clock PCB based on ATmega88 microcontroller, MAS6181B AM receiver, DS1307 RTC. 

Capabilities:
* Time and date displaying
* Weather information displaying
* Alarm handling 
* Automatic and manual remote time / date / weather info synchronization to DCF77 signal
* Time zone configuration
* Time and date maintaining by CR2032 battery
 

<img src="dcf77_clock_final_1.JPG" width="600">


Hardware:
* ATmega88
* MAS6181B DCF77 receiver
* DS1307 RTC + CR2032
* 2x16 HD44760 LCD
* Rotary Encoder + LED + Buzzer

Software:
* C
* Protothreads?
* Own MCU peripherals and external circuits drivers

## Tools
* Autodesk EAGLE v9.6.2

## External links
* Software repository: https://github.com/mlokcewicz/dcf77-clock
