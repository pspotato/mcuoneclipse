readme.txt
----------
Project for a tinyK22 board (NXP K22FN512VLH12) with with FreeRTOS running a ring of WS2812B.

WS2818B data: GPIOD (PTD0...PTD7)
RS-485:       EN (PTB19=> UART0 RTS/PTB2, high active for tx), UART0 TX (PTB17), RX (PTB16)
I2C:
OpenSDA UART: LPUART Rx PTC3, Tx PTC4


Open Points
-----------
- buffering/timeout for RTT shell output
- LED timer too fast/slow?
- flash programming
- watchdog

