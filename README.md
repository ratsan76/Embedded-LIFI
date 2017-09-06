# Embedded-LIFI
Transfer of data with LIFI using ARM controllers
IDE Used : MIKROC PRO for ARM (4.7.1)
ENCODING Used: Manchester 
Data Speed : 1Mbps
Transmitter : In transmitter data is recieved from UART1 and then manchester encoding is done, then transmit data to LED light using UART2.
Reciever : In reciever data is recieved from UART1 from photodetector and manchester decoding is done, and then transmit recieved data over UART2.
Pins fro UART1 : TX - PA9
                 RX - PA10
Pins fro UART1 : TX - PA2
                 RX - PA3
                 
