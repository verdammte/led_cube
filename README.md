# led_cube
I wanted to create the cpu statistic LED monitoring cube from here: https://there.oughta.be/an/led-cube. However, 
it is not compatible with a windows based host computer. The python library it uses does not support Windows. I set out
to make a C# version of the hosting program that is compatible with Windows.

## Requirements (that I know of)
OpenhardwareMonitor's library (OpenHardwareMonitorLib.dll)
SystemManagement.dll
.NET Framework 4.8

I've already included the necessary libraries in the repository.

## Instructions 
There should be no need for instructions, but I'll write them in here when I'm done if they're necessary.

# LED_Cube Itself

## Parts List
- 3D Printed frame (STLs included in repo)
- Raspberry Pi 3B+ (I also tried a Pi 4, but ran into issues with the OpenGL library. I was too lazy to go all in and try to make it work)
- Adafruit LED Matrix Bonnet (the HAT should also work, but I haven't tried it myself)
- MicroUSB PSU for the Pi (it can run ofn the Bonnet's power, but I don't recommend it)
- PSU for the Bonnet (I recommend a 15A 5V brick with a 2,5mm X 5,5mm plug) (https://smile.amazon.com/gp/product/B08764XJ2M/ref=ppx_yo_dt_b_asin_title_o07_s00?ie=UTF8&psc=1)
- 3 LED Matrix panels (I used 64x64 panels with a 2.5 pitch. I'm currently having issues with the panels and may have to change them) (https://smile.amazon.com/gp/product/B07F2BN54N/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)
- Relatively small MicroSD card for the Pi



