# STM32F746G-Discovery-Experiments

STemWin Touch 
=============

Modified the main.c program to add Touchscreen subroutines. Tested with Widget_YTGraph.cpp as the MainTask().

For using VisualGDB, refer: https://sysprogs.com/w/forums/topic/building-stemwin_helloworld-on-stm32f7-discovery-board/

Add stm32746g_discovery_ts.c to Source->Board Specific files and also the ft5336 driver. Easier via menu Project->VisualGDB Properties->Embedded Frameworks->TouchScreen driver (?and ft5336 Driver?).
