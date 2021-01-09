# homekit-lock


This repository is based on the code and the examples provided by Maxim Kulkin.

https://github.com/maximkulkin/esp-homekit-demo

Detailed instructions on how to use the code found here can be found on Maxim's repository. It is the first thing to do before trying the code here.

The hardware used to this project is a BH1750 lux sensor that uses SCL and SCA pins in the ESP8266. It uses the ota-update and the LCM from https://github.com/HomeACcessoryKid/life-cycle-manager/tree/master/homekit%20integration

This is a lock accessory that controls by a relay a magnetic lock. One button (1 and 2 presses - unlock and lock)
It also has a contact sensor to make automations on home app easier
