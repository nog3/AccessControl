# AccessControl
ESP8266 based access control firmware to run on HSBNE's Sonoff TH10 based Doors and Interlocks.

# Hardware Types

There's two main box builds, door and interlock. (Pictures coming)

Door contains a Sonoff TH10, a 240v to 12v cage power supply and uses a GX16 4 pin connector for serial to an external RFID reader and a GX12 to the door bolt/strike.

Interlock contains a Sonoff TH10, a 240v 20A 2Pole NO contactor, a 3.3v RFID reader and a single 20mm threaded case WS2812b led on a custom PCB that is wired into a TRRS connector on the sonoff.

More details on the hardware to come, including pictures.

# Dependancies
* WS2812FX 1.0.4
* Adafruit_NeoPixel 1.1.4
* ArduinoJson
* Websockets 2.1.1
