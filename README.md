# NCP81161-PWMEN-LFPAK33-breakout
Breakout board for NCP81161 gate drivers with PWM and EN inputs and FETs in LFPAK33 like the PSMN1R8-30MLH

## First test successful
The board was tested with an

- STM32G071 (breakout board here: https://github.com/crteensy/STM32G071GBU6_breakout)
- running an experimental branch of AM32, PWM/EN target
- DShot input through a Mamba F405 Mini
- Motor: Mamba 1408 4000KV
- PSU set to 5V, 500 mA current limit

![3D view](https://github.com/crteensy/NCP81161-PWMEN-LFPAK33-breakout/blob/main/NCP81161-PWMEN-LFPAK33-breakout-3dview.png)

This breakout board is designed to facilitate testing of PWM/EN-type firmware on e.g. the STM32G071GBU6 (see here for a matching MCU breakout board: https://github.com/crteensy/STM32G071GBU6_breakout)
