# Apartment-climate-control

This project came about because my apartment lacks central air or anyway to control cooling.


Temperature is measured once a minute and uploaded to Thingspeak. When temperature exceeds temperature threshold, Thingspeak generates an HTTPS alert which is passed to IFTTT and then to turn on my smart plug ie. my portable AC unit.

This code runs on a Adafruit ESP8266 Feather microcontroller along with a Adafruit MCP9808 temperature sensor. 


Big thanks to PythonForUndergradEngineer.com for clear step-by-step guides and making it easy to understand and begin coding in Python. 
https://pythonforundergradengineers.com/micropython-upload-code.html
