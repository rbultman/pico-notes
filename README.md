# pico-notes
Notes on setting up for programming the RPi Pico on Windows

WSL Toolchain
	• To get the tools running on WSL follow this tutorial:
		○ https://github.com/arnegue/Development-for-Raspberry-Pi-Pico-using-WSL
	• To get VS Code working with Pico on WSL, follow these instructions:
		○ https://paulbupejr.com/raspberry-pi-pico-windows-development/
		○ Note:  if you build the examples before getting VS Code working with WSL, you need to delete the build directory.  It looks like the cmake files that are generated when building using the CLI toolchain on WSL are incompatible with the cmake files generated within VS Code.

Building the examples listed here work:  https://datasheets.raspberrypi.com/pico/getting-started-with-pico.pdf

Windows Toolchain
	• Follow the instructions from Chapter 9 of https://datasheets.raspberrypi.com/pico/getting-started-with-pico.pdf
	• When building, the speed is 1/10 to 1/1000 that of the WSL toolchain.
![image](https://user-images.githubusercontent.com/499656/179980239-7c835fd6-fd1b-43fd-a93d-6c7ae1fdad0f.png)
