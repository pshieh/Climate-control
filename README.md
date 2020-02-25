# Apartment-climate-control

A closed control loop to turn on and off a portable AC unit because my apartment doesn't have central air (and because I don't have enough money on constantly run the AC).

This code runs on a Adafruit ESP8266 Feather microcontroller along with a Adafruit MCP9808 temperature sensor. Temperature is measured once a minute and uploaded to Thingspeak. When temperature exceeds temperature threshold, Thingspeak generates an HTTPS alert which is passed to IFTTT and then to turn on my smart plug ie. my portable AC unit.

Big thanks to PythonForUndergradEngineer.com for clear step-by-step guides and making it easy to understand and begin coding in Python. 
