# Password-Protector
A Short C++ Script to Copy and Erase Data from Windows Clipboard

The easiest way for a password to be compromised is someone watching you type it in.<br>
This script uses the windows API to make clipboard modifications so that you can just paste in your passwords.<br>
It then erases the clipboard data, and your password is not visibly entered as perceived by your surroundings.<br>

I recommend compiling the executables for your most frequent apps, and keeping them on a USB drive and/or in an encrypted folder.  For those that are extremely password cautious, you could also inject keys with an Adafruit MCU or Raspberry Pi by emulating a keyboard HID device.<br>
