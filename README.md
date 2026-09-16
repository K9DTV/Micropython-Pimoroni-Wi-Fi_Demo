# Micropython-Pimoroni-Wi-Fi_Demo

[![Compile](https://github.com/K9DTV/Micropython-Pimoroni-Wi-Fi_Demo/actions/workflows/compile.yml/badge.svg)](https://github.com/K9DTV/Micropython-Pimoroni-Wi-Fi_Demo/actions/workflows/compile.yml)
[![Release](https://img.shields.io/github/v/release/K9DTV/Micropython-Pimoroni-Wi-Fi_Demo)](https://github.com/K9DTV/Micropython-Pimoroni-Wi-Fi_Demo/releases/latest)

**Status:** Final release **v1.0.0** — project closed out.

**Project page:** https://k9dtv.com/project-pico-wifi.html

Basic Wi-Fi demo on the RP Pico 2 W using Pimoroni MicroPython.

This project uses the following items:

(1) RP Pico 2 W					(pishop.us)

(1) Waveshare UPS Module for Raspberry Pi Pico 	(AliExpress.us)

(1) Expansion Board Pi Pico Dual GPIO Expander 	(AliExpress.us)

(1) Pimoroni Pico Display Pack 2.0             (Pimoroni.com)

(1) 14500 battery                              (Amazon.com)

![20250214_144243](https://github.com/user-attachments/assets/a494b83a-1509-4828-83d3-ab63bf2453a1)


Other products may work as well as other suppliers (YMMV).

Put your SSID and password in secrets.py.
Load the following onto the Pico local directory using Thonny (or any other program that works):

secrets.py

main.py

pico_off.jpg

pico_on.jpg

Run main.py

The display and Thonny console should show you the local IP of the Pico's web server.
Paste this address in a web browser address bar and hit enter.

NOTE: If running on battery power, it may take some time to connect and for the LCD screen to come up.

A web page should come up.

![Screenshot 2025-02-14 150940](https://github.com/user-attachments/assets/c50a31c8-6f99-43b6-ab48-5673441958e7)

Use the Turn ON/OFF buttons to control the onboard LED.

![Pix_system](https://github.com/user-attachments/assets/35be2125-01fa-4998-82d3-115bc03c9951)

And the LCD display should change as well.
