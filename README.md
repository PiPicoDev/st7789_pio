# st7789_pio

This is currently just pico-examples\pio\st7789_lcd with the defines set for a Pimoroni Display Pack 2.0 / 2.8

The interesting thing is that it works over SPI but without using the hardware Pico SPI but instead using PIO to do the communication with the display

ATM this is write only but the reason for this experiment is to get read access to the ST7789 (yet to be done of course)

Note that the original version defines a pin for LCD_RESET while the Display Packs (and all others I've seen) have this pin hard-wired to RUN

Tested on a Pico (the basic one) with a Display Pack 2.0

Appears to run about 30FPS (need to add frame timing to it later)
