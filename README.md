# switchbot-minihub

Just some stuff around the Switchbot Minihub

Used FTDI USB to serial HW-475

| FTDI | Minihub |
-------- |----------
| GND  | GND |
| RX | TX01 |
| TX | RX |

On the hub:
- Jumped GPIO0 to GND
- Jumped RST to TXS

- FTDI already connected to computer
- Plug micro USB in for power

In putty:
- baud: 115200
- logging: printable output
