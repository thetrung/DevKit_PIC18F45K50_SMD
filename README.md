DevKit PIC18F/USB-B
=====================
Basic USB Type-B DevKit I made to learn about PIC18F45XX microcontroller.

![overview](https://github.com/thetrung/DevKit_PIC18F/blob/master/Images/Sch_DevKit_PIC18F.png)

**It was initially for USB Type-C, but seem like I was wrong about how popular it actually is in my local stores, so change of plan : switching back to USB Type-B from Rev.2 for ease of self-soldering the boards. But very funny, on Rev.2, while changing the USB-Port, I realize how everything seem to be a little bit closer to what I think it should be. There were a short-circuit (for the 2nd-time) that I didn't realize right inside the USB-port.**

### 1. Basic functionality :
- USB-powered 5V supply.
- USB-HID controllable with PIC18F45k50 with D+/D- pins.
- Reset Button -> Trigger MLCR-pin pull-down -> GND.
- Programming/Debugging with PICKIT-3 via ICSP pins.
- 5 pluggable PORTS : RA, RB, RC, RD, RE.
- LED at RD0 for Blink Test.

![3d_parts](https://github.com/thetrung/DevKit_PIC18F/blob/master/Images/3D_View.png)
![back](https://github.com/thetrung/DevKit_PIC18F/blob/master/Images/Back.png)

### 2. TODO / Future extensions :
- Add Array : 
    - 4x4 12mm-Buttons pad.
    - 4x4 LEDs grid.
    - 16 Relays
      
- Add Gyro sensor.
- Add distance sensor.
- Add 12V Booster support.
- Add built-in UART w/ CH340.
- Add LCD2004 support, with/without I2C module.
- Add WIFI/LoRA/Bluetooth by ESP32 support (?).
  
