# xavier_nx_breakout
Header breakout for NVIDIA Jetson Xavier NX Development Kit.

This breakout board overcomes the limitation of the 2uA maximum output current (per pin) of the TXB0108 8-Bit Bidirectional Voltage-Level Translators used for the GPIOs of the J12 header.

The breakout provides the following:

* UART1_TX and UART1_RTS buffered with non-inverting Schmitt triggers.
* PWM capable GPIO07, GPIO12 and GPIO13 buffered with non-inverting Schmitt triggers.
* Pixhawk compatible interface (JST-GH 6-pin 1.25 mm pitch) provided for UART1.
* Stemma QT / Qwiic (JST-SH 4-pin 1.0 mm pitch) compatible interface provided for I2C0.
* Pixhawk compatible interface (JST-GH 4-pin 1.25 mm pitch) provided for I2C1.
