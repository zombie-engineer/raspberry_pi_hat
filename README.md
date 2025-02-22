Raspberry PI hat.

Convenience expansion board for raspberry pi development.

Features:

JTAG connector for debug
Raspberry Pi has JTAG pins, TDO, TDI, TMS, TCK, etc. They are distributed in chaotic way across pin connector.
For this reason it is good to create a nice little connector, especially designated for JTAG

Micro USB connector for uart output
Raspberry PI has special pins for UART. This pins are routed to FTDI FT232H chip, which further redirects uart
data to USB.
Datasheet for the FTDI FT232H is here:
https://ftdichip.com/wp-content/uploads/2024/09/DS_FT232H.pdf
