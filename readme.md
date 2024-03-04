[한국어](https://github.com/FTIndustries/BMI270-Breakout/blob/main/readme-ko.md)
# FTIndustries BMI270 IMU breakout
![preview](https://github.com/FTIndustries/BMI270-Breakout/blob/main/3dpreview.png?raw=true)\
Sensor breakout using Bosch Sensortec's BMI270 6DoF IMU, supports Sparkfun Qwiic system. It uses the same form factor with well-known unbranded BMI160 boards and it is pin-to-pin compatible. 

## Specification
Supply Voltage (VDD): 1.71~3.6V \
Logic Low (VIL): 0.3\*VDD max \
Logic High (VIH): 0.7\*VDD min \
Current consumption: around 1mA at performance mode \
for more information, see [BMI270 techdata](https://www.bosch-sensortec.com/products/motion-sensors/imus/bmi270/#technical)

## I2C address
the module uses I2C address 0b1101000 (0x68) by default. to change it to 0b1101001 (0x69), solder the jumper at the back side of the module.