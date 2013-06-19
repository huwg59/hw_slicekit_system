sliceCARD overview
===================

Pack contents
-------------

   * One XA-SK-UART-8 sliceCARD
    
RS232 capability
----------------

8 UARTs are provided on two 8-bit ports. An RS232 signalling level option is provided by four SP3222EB RS232 
transceivers, each handling 4 tX or 4 RX lines. The EN_N enable pins of the transceivers are controlled by 
populating a jumper between pins 25 and 26 of header J3. If that jumper is populated then RS232 is disabled 
and TTL inputs/outputs for all UARTs can be accessed via J3, otherwise RS232 inputs/outputs for all UARTs can 
be accessed via J4. 

Fixed oscillator 
-----------------

A 1.8432 MHz oscillator provides a fixed master reference frequency which is input into the xCORE device on a 
1-bit port to allow the sc_multi_uart transmitter module software to obtain precise timing against standard UART 
baud rates. 

DB9 connector
-------------

UART channel 0 (RX and TX) can be accessed either via pins 1 and 2 of J3 or J4, or via the DB9 connector. In the 
latter case, RS232 mode needs to be enabled as above.


