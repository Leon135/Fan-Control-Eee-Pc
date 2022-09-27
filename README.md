# Fan-Control-Eee-Pc

## Description

This script was made to control eepc fans. <br />
I tried to use lm-sensors but they don't work for me. <br />
So i wrote this script. <br />
It changes /sys/class/thermal/cooling_device*/cur_state to the "mode" of fans. <br />
Higher == faster <br />
And it works! <br />

## Installing
Just download it and put it in your /bin/bash folder.

## Usage
sudo fan_control (temp/check/set) (set speed) <br />
<br />
Temp is for current cpu temperature <br />
Check is for checking which "mode" are fans on. <br />
Set is setting the speed. (max 10) <br />
<br />
Set speed is argument only for set. <br />
