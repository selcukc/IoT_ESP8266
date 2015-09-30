# IoT_ESP8266
Tiva LaunchPad Internet of Things with ESP8266

In present work, I aim to control servo motor as an Internet of Things(IoT) so i use ESP8266 , which is the low cost wifi module (approx. 3$), to establish connection between Tiva LaunchPad(as a client) and Computer(as a server) via internet with Transmission Control Protocol (TCP). I use Java application to create server to control servo on the PC side of the project. One can see the Java Application in below link.

https://www.youtube.com/watch?v=2NBJP0-isrg

Setup & Pin Configuration

ESP8266 Pin versus Tiva Launchpad

First link the ESP8266 VCC pin to CH_PD pin via shortcut
VCC -> 3.3V, GND -> GND,  RXD -> PB1, RST -> PD0, TXD -> PB0.
To control servo please link the servo signal pin to PC5(pin)
