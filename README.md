# piPower
This is a fork of Mike's project (consoleLED). It uses ANSI control codes to display a red "ON" status of
the power LED in the top right corner of the terminal screen as shown here:
![ON status](https://cloud.githubusercontent.com/assets/5799357/7383169/99ec1c64-ede8-11e4-920a-72589e2d3ad7.png "powerLED")

---
Monitor input power of the raspberry pi 

- Supports recent Pi models A+, B+ , Pi-2  - not older A/B

ledcheck.py  - logs status of powerLED remotely, warns if voltage is under 4.63v, 
shuts down if low for 4+ seconds.

consoleLED.py - shows LED status in the console (e.g. over SSH)
