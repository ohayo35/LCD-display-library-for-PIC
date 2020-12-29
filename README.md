This C based library is meant for the following LCD display modules : 
1602 ( 2 lines x 16 characters) 
2002 ( 2 lines x 20 characters) 
1604 ( 4 lines x 16 characters) 
2004 ( 4 lines x 20 characters)

It has been tested with the following environment : 
Software : MPLAB X v5.30, XC8 v2.10 and MCC plugin v3.95 
Hardware : PICDEM 2 PLUS board with PIC16F18875 (40 pins) 
The LCD module on PICDEM2+ is Ocular OM16214 which uses a SPLC782A LCD controller (compatible with HD44780 / KS0066U / ST7066U / ... )

It is totally modular. The pin used for any signal can be configured by the library. 
Even the 4 data can be used from different ports on the microcontroller It is NOT using delays but uses the busy bit from the LCD display IC making it easier to port to different speeds
