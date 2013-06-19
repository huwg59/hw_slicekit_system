sliceCARD overview
===================

Pack contents
-------------

   * One XA-SK-SDRAM sliceCARD

Random Access Memory
--------------------

This slice provides 8 Megabytes of random access memory via an ISSI 6400 
Synchronous DRAM. It is suitable for burst access only; random access is 
possible but performance will be very significantly degraded. The associated 
SDRAM Control xSOFTip component can operate this memory at clock speeds up to 
40 MHz, yielding an aggregate performance of 80 MBytes/sec.

Reduced pinout
--------------

The SDRAM slice uses a technique of reusing the same xCORE GPIO pins for both 
address and data. This optimization is possible thanks to the soft nature of 
the associated xSOFTip SDRAM controller component. In addition, a NOR gate on 
the slice generates the data strobes (UDQM and LDQM on the memory chip) from 
CAS# and WE#. These features are described more fully in the SDRAM Controller 
xSOFTip component documentation.

Taken together, these features permit the addition of a high performance SDRAM 
subsystem to any xCORE application using only 20 pins.


