# MPU6050-with-the-Arduino

The GY-521 module is a breakout board for the MPU-6050 MEMS (Microelectromechanical systems) that features a 3-axis gyroscope, a 3-axis accelerometer, a digital motion processor (DMP), and a temperature sensor. The digital motion processor can be used to process complex algorithms directly on the board. Usually, the DMP processes algorithms that turn the raw values from the sensors into stable position data. This tutorial gives only a brief introduction to the GY-521/MPU-6050. In particular, it is shown how to retrieve the raw sensor values. The sensor values are retrieved by using the I2C serial data bus, which requires only two wires (SCL and SDA). If you plan to use the full range of features or require reliable and stable position data, then I recommend to have also a look at ready-to-use libraries. Please follow this link to find an excellent library with many

for circuitry
//5V > VCC
//GND > GND
//A4 > SDA
//A5>SCL

refer circuitry

![wiring](https://user-images.githubusercontent.com/109905492/198830622-621e2b2e-cf18-4b20-9888-c92cae347013.png)
