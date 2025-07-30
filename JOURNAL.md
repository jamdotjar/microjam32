# 2025/09/29
Finally giving an effort into starting this properly. I've been humming and hawing with it over the past few weeks, but now I'm actually giving this a good shot!
In that time, the main things I did were:
Look into the different esp chips, get some reference of the existing seeed devboards, figure out how much space I have to work with. After the buttons, USB-C and an antenna connector it looks like the answer is: "Not much" ( abt 12.5x10.5mm 😭 )

<img width="669" height="554" alt="image" src="https://github.com/user-attachments/assets/7cc59cf0-7d88-4772-9dae-403707a68ae5" />

So, I went through the esp product selector, and it looks like the ESP32-PICO-V3-02 is the most capable overall ( and decently easy to work with ). It also leaves a fair bit of free space that I can work with, so hopefully the additional circuitry shouldn't be too much of a squeeze. Speaking of additional circuitry, my goal is to replicate a fair few functions of the Seeed studio Xaio Esp32 S3. braindump of those:
- battery charge management
- 11 GPIO ( specifically with this pinout or as close as I can get ): <img width="645" height="357" alt="image" src="https://github.com/user-attachments/assets/c7b344ce-55e6-4ad2-be31-c9cccf801299" />
- deep sleep mode?
so yeah, hopefully this goes well. Time to go read some datasheets

> * time spent: 3.5hrs (over the past few weeks, obligatory catchup guesstimate as I offically start the project)*
