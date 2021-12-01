# STM32WLE5JC-Blinky-StopMode

This is a simple program to measure minimal power consumption on a 
STM32WLE5JC based board. Everything is disabled but the RTC peripheral
which is used to wake up the MCU. The program blinks a few times
and then goes 10 seconds into Stop2 mode which is the lowest
"reasonable" power mode.

I have measured the Seeed [Lora-E5-Mini](https://wiki.seeedstudio.com/LoRa_E5_mini/) at 90uA and the 
[STM32WL MAMWLE-C1](https://www.tindie.com/products/makertronika-labs/penguino-stm32wl-mamwle-c1-lora-dev-board/)
at 9uA, which is a very nice result.
