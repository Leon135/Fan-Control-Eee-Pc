# Fan-Control-Eee-Pc

## Description

This script was made to control eepc fans. \n
I tried to use lm-sensors but they don't work for me. \n
So i wrote this script. \n
It changes /sys/class/thermal/cooling_device*/cur_state to the "mode" of fans. \n
Higher == faster \n
And it works! \n

## Installing
Just download it and put it in your /bin/bash folder.

## Usage
sudo fan_control (temp/check/set) (set speed)

Temp is for current cpu temperature \n
Check is for checking which "mode" are fans on. \n
Set is setting the speed. (max 10) \n
\n
Set speed is argument only for set. \n
