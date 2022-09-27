# Fan-Control-Eee-Pc

## Description

This script was made to control eepc fans. \
I tried to use lm-sensors but they don't work for me. \
So i wrote this script. \
It changes /sys/class/thermal/cooling_device*/cur_state to the "mode" of fans. \
Higher == faster \
And it works! \

## Installing
Just download it and put it in your /bin/bash folder.\

## Usage
sudo fan_control (temp/check/set) (set speed)\
\
Temp is for current cpu temperature \
Check is for checking which "mode" are fans on. \
Set is setting the speed. (max 10) \

Set speed is argument only for set. \
