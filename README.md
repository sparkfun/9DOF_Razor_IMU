9_Degrees_of_Freedom_-_Razor_IMU
======================================
The 9DOF Razor IMU incorporates three sensors - an ITG-3200 (MEMS triple-axis gyro), ADXL345 (triple-axis accelerometer), and HMC5883L (triple-axis magnetometer) - to give you nine degrees of inertial measurement. The outputs of all sensors are processed by an on-board ATmega328 and output over a serial interface. This enables the 9DOF Razor to be used as a very powerful control mechanism for UAVs, autonomous vehicles and image stabilization systems.

The board comes programmed with the 8MHz Arduino bootloader (stk500v1) and some example firmware that demos the outputs of all the sensors. Simply connect to the serial TX and RX pins with a 3.3V FTDI Basic Breakout, open a terminal program to 57600bps and a menu will guide you through testing the sensors. You can use the Arduino IDE to program your code onto the 9DOF, just select the 'Arduino Pro or Pro Mini  (3.3v, 8mhz) w/ATmega328' as your board.

The 9DOF operates at 3.3VDC; any power supplied to the white JST connector will be regulated down to this operating voltage - our LiPo batteries are an excellent power supply choice. The output header is designed to mate with our 3.3V FTDI Basic Breakout board, so you can easily connect the board to a computer's USB port. Or, for a wireless solution, it can be connected to the Bluetooth Mate or an XBee Explorer.

Features:

9 Degrees of Freedom on a single, flat board:
ITG-3200 - triple-axis digital-output gyroscope
ADXL345 - 13-bit resolution, ±16g, triple-axis accelerometer
HMC5883L - triple-axis, digital magnetometer
Outputs of all sensors processed by on-board ATmega328 and sent out via a serial stream
Autorun feature and help menu integrated into the example firmware
Output pins match up with FTDI Basic Breakout, Bluetooth Mate, XBee Explorer
3.5-16VDC input
ON-OFF control switch and reset switch
Dimensions: 1.1" x 1.6" (28 x 41mm)
