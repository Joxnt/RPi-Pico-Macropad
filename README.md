# RPi-Pico-Macropad
A simple 9 key macropad featuring a display.

# items used
- 9x mechanical keyboard switches
- 1x Raspberry Pi Pico
- 1x waveshare 1.5" OLED display
- 3d printed case
- 9x keycaps

# Installing files and booting
1. Download Circuit Python from https://circuitpython.org/board/raspberry_pi_pico/
2. install Circuit Python by dragging the .UF2 file into the pico's folder
3. place all the files from the repo into the CIRCUITPY drive

# Accessing the drive once it is installed
In order to access the Pico's drive once the program is installed, you must hold down button 9 whilst plugging the Pico into your device.

# How to create pages and enter the info
Make a new text file. In this file you can put the bindings for the buttons and what they do. The numbers that refer to the keys can be found in the keycode.txt file in the adafruit_hid library. Other pages can be reffered to by putting their file name in the page. On the line after the keybind, put what you want to be displayed on the OLED display. To be able to access the page, you need to create a reference to it in another page such as home.txt.
