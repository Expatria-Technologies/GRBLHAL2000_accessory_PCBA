# RGB Plugin PCB for GRBLHAL

![Logo](/readme_images/logo_sm.jpg)

A simple LED driver module for the 'datron-like' RGB plugin in GRBLHAL:

https://github.com/5ocworkshop/grblhal-rgb-plugin

<img src="/readme_images/board_overview.png" width="600">

The unit accepts 12-24V input to the two pin terminal block and can drive ~1A at 12V to each color channel via the four pin output terminal.  Connection is made directly to the AUX IO header on the GRBLHAL2000 board.  There are two Aux connectors on the RGB module so that more units can be daisy-chained together, or so that the unused output may be accessed for additional applications.

