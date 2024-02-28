[English](https://github.com/FTIndustries/BMI270-Breakout/blob/main/readme.md)
# FTIndustries BMI270 IMU breakout
![미리보기](https://github.com/FTIndustries/BMI270-Breakout/blob/main/3dpreview.png?raw=true)\
Bosch Sensortec의 BMI270 6DoF IMU를 사용한 센서 브레이크아웃 모듈입니다. Sparkfun Qwiic 시스템을 지원합니다. 브랜드 없는 BMI160 보드와 동일한 폼 팩터를 사용하며 핀 간 호환이 가능합니다.

## 사양
Supply Voltage (VDD): 1.71~3.6V \
Logic Low (VIL): 0.3*VDD max \
Logic High (VIH): 0.7*VDD min \
Current consumption: around 1mA at performance mode \
자세한 내용은 [BMI270 기술 데이터](https://www.bosch-sensortec.com/products/motion-sensors/imus/bmi270/#technical)를 참조하세요.

## I2C 주소
모듈은 기본적으로 I2C 주소 0b1101000(0x68)을 사용합니다. 0b1101001(0x69)로 변경하려면 모듈 뒷면의 점퍼를 납땜하세요.