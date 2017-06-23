How it works?
On the EasyRaceLapTimer (Raspberry PI) running the infoserver on port 3007.
The NodeMCU Module connect via Wifi to this service and send all the data via UART.
The MinimOSD send all the data from the rx line to the first line of the OSD 


[X] First off all you need a Ground-Station Setup (Secondary FPV Receiver like ImmersionRC FPV DUO5800)
[X] You need an Secondary Osd like the minimOSD. Upload the Charset and the Arduino File
[X] The NodeMCU module to Connect to the EasyRaceLapTimer_OSD

The Wire is very simple. Connect the GND and the TX Pin from the NodeMCU to the MinimOSD (RX and GND)

sorry for my englisch
