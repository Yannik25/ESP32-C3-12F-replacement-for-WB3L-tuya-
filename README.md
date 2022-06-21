# ESP32-C3-12F-replacement-for-WB3L-tuya-

# This documentation is especially for following product but may apply to other Tuya devices:
https://www.amazon.de/gp/product/B08VRJQKNL

I first tried using the ESP8266, but that chip is not powerful enough to control the RGB and the Cold-Warm White LED Channels in parallel. There only software PWM is possible.

The ESP32 is capable of handling multiple hardware PWM channels.

# Software:
I tried ESPHome - there are some issues with reboots or compiling.
For now I use Tasmota Version 12.0.1

IMG of tasmota config (TBD):

In the console enter following to enable independent control of RGB and CW-WW LEDs:
SetOption37 128

IMG from pcb (TBD):
