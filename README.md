# ClockExample

基于ESP8266的无线时钟

A wireless clock basing on ESP8266.

**中文版**
## 材料
**Mcu**: ESP8266

**开发工具**: Arduino

## 注意
把tft-espi库里的"User_Setup.h"我们仓库目录下的。

## 特点
**1)即使天气**

**2)Ntp授时**

**English Version**
## Meterials
**Mcu**: ESP8266


**Develop Tool**: Arduino

## Notes
This program should runs with a TFT screen(240*135). However, the default configuration of the TFT-eSpi library doesn't match. You should replace the "User_Setup.h" in TPT-eSpi library with file with same name in our repository.

## Features
**1)Instant weather** Program can fetch the weather information via China Weather, including AQI(Air Quality Index, China standard), temperature, humidity, etc. It can be flushed on the screen and it will be updated per five mins.

**2)Ntp** Program can proofread the time through Ntp Server(aliyun).
## Preview / 预览
![clock](https://github.com/f13T2ach/ClockExample/assets/101922505/439b76f3-68b3-4343-a26e-032745d564fe)
