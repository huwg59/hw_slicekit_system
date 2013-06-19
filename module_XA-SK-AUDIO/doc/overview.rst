sliceCARD overview
===================

Pack contents
-------------

   * One XA-SK-AUDIO sliceCARD

4 channel audio
----------------

Four input and four output channels are provided on the sliceCARD via an 
I2S interface to two CS4270 stereo audio codecs with a shared 2-wire bus 
for configuration. The xSOFTip I2S driver component drives all 4 channels 
in both directions at sample rates up to 192 kHz and takes care of codec 
configuration. Audio clock generation is provided via a CS2100-CP programmable PLL.

MIDI 
----

MIDI In and MIDI Out connectors are provided. A stand alone MIDI xSOFTip component 
to work with this sliceCARD is under development.

S/PDIF Transmit
---------------

An S/PDIF digital audio output is provided on the board. A stand alone S/PDIF 
transmit xSOFTip component to work with this sliceCARD is under development.



