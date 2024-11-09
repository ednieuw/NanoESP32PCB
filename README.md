# Nano ESP32 word clocks.
On this page PCB (printed circuit boards) designs are shown designed for the Arduino Nano ESP32.
![image](https://github.com/user-attachments/assets/4bee4116-e8eb-43e1-89f7-a30ab3eb7112)<br>
Soldered boards. On all it is possible to attach a LDR, rotary encoder and DS3231 RTC

The Arduino Nano ESP32 PCB is used to built a word clock with WS2812 or SK6812 LED-strips.

The larger Ultimate Arduino Nano ESP32 PCB is designed to use shift registers combined with Darlington array IC's to turn on white 12V LEDs connected to one of the 24 pins. With this PCB it is also possible to use WS2812/SK6812 and many more hardware.

The Arduino Nano ESP32 small PCB is a small PCB with connections for a DS3231 RTC module and a rotary. It is designed for small spaces.
The DS3231 RTC module can be used in places without a WIFI connection.

The Arduino Nano ESP32 HC595 shiftregister PCB is for small places with only pulse width modulation from 5V to 12V. Rotary and DS3231 must be connected with wires. The PCB is nice for testing or to be used in small spaces in a clock. It has 32 lines to switch 12V LEDs.

# Arduino Nano ESP32 PCB
PCB for Nano ESP32 for SK6812/WS2812 LED strip, DS3231 RTC, 74AHCT125 Level shifter

See https://github.com/ednieuw/Arduino-ESP32-Nano-Wordclock

![Nano-ESP32-V04](https://github.com/user-attachments/assets/0a5dc063-3f68-4590-b57e-a2cfc42f2139)

![NanoESP32-V04-3D](https://github.com/user-attachments/assets/c0bad2fc-b6cb-43bb-b337-e3dcf18a8eec)
![NanoESP32-V04-2D](https://github.com/user-attachments/assets/619cf270-53bd-4515-a15f-15e4fcc81632)


# [Ultimate Arduino Nano ESP32 PCB](https://github.com/ednieuw/NanoESP32-BW-RGBW-clock)

[Special designed for a RGB(W)](https://github.com/ednieuw/Arduino-ESP32-Nano-Wordclock) and white led strip word clock.(https://github.com/ednieuw/Woordklok-witte-LEDs).


Design V002 is without errors ready to use but some components cq connections are not in optimal position.<br> 
PCB design V005 has some minor part and text location improvements. 

[Soldering instructions for One PCB with two several possibilities](https://github.com/ednieuw/NanoESP32-BW-RGBW-clock)

[Dedicated page for the use of this PCB here](https://github.com/ednieuw/NanoESP32-BW-RGBW-clock).

![PCB-ESP32WoordklokV005](https://github.com/user-attachments/assets/9e4f3514-de9f-473d-befb-e5ae368d3bb1)

![PCB-ESP32WoordklokV005](https://github.com/user-attachments/assets/92176798-d462-43d1-b163-7c878dadbfb0)

Designs V001, V003 and V004 has missing connections as shown on the pictures. These designs are kept for my own reference.<br> 
![PCBV001V002](https://github.com/user-attachments/assets/dfc4f481-87f7-44bd-87c5-56e502ec07b0)

![PCBV003V004](https://github.com/user-attachments/assets/5a68836e-a269-4a7f-9adb-8a0c8d68cb97)



# Arduino Nano ESP32 small PCB

This PCB is designed to be used in the small side of a clock. It contains the minimum amount of parts.
There are connections for an optional rotary encoder to control the optional DS3232 RTC time module when WIFI/NTP is not available.

[See here for the word clock for this PCB](https://github.com/ednieuw/Arduino-ESP32-Nano-Wordclock)

![V02 Small Nano ESP32](https://github.com/user-attachments/assets/8e74c62e-4558-4bc3-980b-12116fde90aa)

![V02 Small Nano ESP32-3D](https://github.com/user-attachments/assets/5982dfa4-df37-43ca-9d5b-2ef0064d8268)

![SmallV02PCBlife](https://github.com/user-attachments/assets/f0c82213-8977-4391-a50c-25f92cd3d5d7)



# Arduino Nano ESP32 HC595 shiftregister PCB

![HC595ESP32V001](https://github.com/user-attachments/assets/02effc77-bdda-45f5-ae33-9528c1fe3c98)

![V01-ESP32-HC595-3D](https://github.com/user-attachments/assets/6047da68-eb7f-4b65-94bd-2603567507c3)
