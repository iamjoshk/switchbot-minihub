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


- FTDI already connected to computer
- Plug micro USB in for power

In putty:
- baud: 115200
- logging: printable output

And then I broke the micro usb port on the board and discovered that my FTDI is only supplying 2.8v from the 3.3v pin.
