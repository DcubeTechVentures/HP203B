[![HP203B]( HP203B_I2CS.png)](https://www.controleverything.com/content/Catchall?sku=HP203B_I2CS)
# HP203B
HP203B Barometer and Altimeter Sensor.

The HP203B is a device that measures the altitude, pressure and the temperature by an internal 24-bit ADC

This Device is available from ControlEverything.com [SKU:  HP203B_I2CS]

https://www.controleverything.com/content/Catchall?sku=HP203B_I2CS

This Sample code can be used with Raspberry pi, Arduino, Particle and Beaglebone Black.

## Java
Download and install pi4j library on Raspberry pi. Steps to install pi4j are provided at:

http://pi4j.com/install.html

Download (or git pull) the code in pi.

Compile the java program.
```cpp
$> pi4j HP203B.java
```

Run the java program.
```cpp
$> pi4j HP203B
```

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python HP203B.py
```

## Arduino
Download and install Arduino Software (IDE) on your machine. Steps to install Arduino are provided at:

https://www.arduino.cc/en/Main/Software

Download (or git pull) the code and double click the file to run the program.

Compile and upload the code on Arduino IDE and see the output on Serial Monitor.


## Particle Photon

Login to your Photon and setup your device according to steps provided at:

https://docs.particle.io/guide/getting-started/connect/photon/

Download (or git pull) the code. Go to online IDE and copy the code.

https://build.particle.io/build/

Verify and flash the code on your Photon. Code output is shown in logs at dashboard:

https://dashboard.particle.io/user/logs


## C

Setup your BeagleBone Black according to steps provided at:

https://beagleboard.org/getting-started

Download (or git pull) the code in Beaglebone Black.

Compile the c program.
```cpp
$>gcc HP203B.c -o HP203B
```
Run the c program.
```cpp
$>./HP203B
```
#####The code output is the altitude in meters, pressure in Pa and temperature reading in degree celsius and fahrenheit
