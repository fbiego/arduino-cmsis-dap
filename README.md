# arduino-cmsis-dap

CMSIS-DAP USB-SWD/JTAG HID adapter firmware for Pro Micro and Teensy 3.2 boards

Copyright (C) 2016 Phillip Pearson <pp@myelin.nz>

based on the <a href="https://github.com/mbedmicro/CMSIS-DAP">CMSIS-DAP Interface Firmware</a>

Copyright (c) 2009-2013 ARM Limited

This is a port of the core of ARM's CMSIS-DAP firmware to the Arduino environment,
which lets you turn a <a href="https://www.sparkfun.com/products/12587">Pro Micro</a> (or $3.50 clone from China)
or <a href="https://www.pjrc.com/store/teensy32.html">Teensy 3.2</a> into a
CMSIS-DAP USB adapter, which you can use with OpenOCD and mbed to program and debug ARM chips using the SWD protocol,
and also with OpenOCD to program and debug various chips using JTAG.

See [`arduino-cmsis-dap.ino`](https://github.com/fbiego/arduino-cmsis-dap/blob/master/arduino-cmsis-dap.ino) for installation details.
