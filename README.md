# STM32F746G-Discovery-Experiments

STemWin Touch 
=============

Modified the main.c program to add Touchscreen subroutines. Tested with Widget_YTGraph.cpp as the MainTask().

For using VisualGDB, refer: https://sysprogs.com/w/forums/topic/building-stemwin_helloworld-on-stm32f7-discovery-board/

Add stm32746g_discovery_ts.c to Source->Board Specific files and also the ft5336 driver. Easier via menu Project->VisualGDB Properties->Embedded Frameworks->TouchScreen driver (?and ft5336 Driver?). Also include stm32746g_discovery_ts.h & stm32746g_discovery_lcd.h in main.h.

![stm32f746-touch-stemwin-1](https://cloud.githubusercontent.com/assets/192318/12576340/f4c0fe80-c438-11e5-9f67-1d7d973c1d35.jpg)
![stm32f746-touch-stemwin-2](https://cloud.githubusercontent.com/assets/192318/12576341/f4d00754-c438-11e5-8727-a50df39ef08e.jpg)
