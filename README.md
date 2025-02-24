# ESP32-Installer
This script will prepare a Linux OS for ESP32 development.

You can read more on [my website](https://ardawan.tech/).

This script is not tested on MacOS.

## Usage
```
$ git clone https://github.com/ardawan/ESP32-Installer.git
$ cd ESP32-Installer
$ ./esp32-installer -h
```

The installation steps:
- Installing all dependencies
- Make "esp" directory in the $HOME directory
- Clone the ESP-IDF repository. If it's already cloned, the script is skip this step
- Run & set the ESP tools from the cloned repository
- Set IDF environment variable and make an alias to the shell's session file
