# ESP01 support

This directory contains eagle schematics for LibTeleinfo on ESP01.

ESP01 is very cheap (a couple of dollars).
But the serial link seems to be less reliable (I often had read errors).
Code has been reworked to validate electrical counter serial input based on known tokens/keywords.

A simple schematics like the one proposed below is doing well the job.

![ESP01 schematics](https://github.com/r2d2/LibTeleinfo/blob/master/eagle_wifinfo_esp01/ESP01_schematics.png "ESP01 schematics")