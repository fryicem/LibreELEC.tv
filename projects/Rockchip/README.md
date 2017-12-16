# Rockchip

This project is for Rockchip SoC devices

## Devices

* [ASUS Tinker Board](devices/TinkerBoard)
* [PINE64 ROCK64](devices/ROCK64)
* [mqmaker MiQi](devices/MiQi)
* [Popcorn Hour RockBox](devices/RockBox)

## Links

* https://github.com/rockchip-linux
* http://opensource.rock-chips.com

## Useful debug commands

* `cat /sys/kernel/debug/dri/0/summary`
* `cat /sys/kernel/debug/dw-hdmi/status`
* `cat /sys/kernel/debug/clk/clk_summary`
* `hexdump -C /sys/class/drm/card0-HDMI-A-1/edid`
* `edid-decode /sys/class/drm/card0-HDMI-A-1/edid`
