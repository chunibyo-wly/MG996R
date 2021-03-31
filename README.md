NodeMCU + MG996R

[demo](https://www.bilibili.com/video/BV1BK411c7LK)

1. MG996R需要5V电压才能正常工作，使用NodeMCU的3.3V不能正常工作。
2. NodeMCU通常有3种版本，淘宝搜索第一个是V3版，[版本比较链接](https://frightanic.com/iot/comparison-of-esp8266-nodemcu-development-boards/)。
3. 这里使用`VU` GPIO口给MG996R提供5V工作电压，[参考issue](https://github.com/nodemcu/nodemcu-devkit-v1.0/issues/9#issuecomment-239635540)。