# awesome config
This is my configuration for Awesome v3.5.6 window manager

## Tested on


**Hardware**

Dell XPS 13 (9343) 


**Operating system**

Distributor ID:	Ubuntu

Description:	Ubuntu 14.04.3 LTS

Release:	14.04

Codename:	trusty

Kernel : 3.13.0-37-generic


## Features

- Zenburn theme
- Volume status, Memory status, Cpu status And battery status
- Key hooks for Volume control , Brtiness control (FN + volumeup , FN + volumedown  etc.)
- Custom wallpaper


## Installation


**Pre requirement**

Backlight control

    sudo apt-get install xbacklight

Battery status

    sudo apt-get install lua5.1 luarocks libgirepository1.0-dev acpi
    sudo luarocks install battery_status

Latest version of awesome

    sudo add-apt-repository ppa:klaus-vormweg/awesome
    sudo apt-get update
    sudo apt-get install awesome

    
**Install the configuration** 

    cd ~/.config
    git clone https://github.com/rafel/awesome.git awesome


Restart awesome

