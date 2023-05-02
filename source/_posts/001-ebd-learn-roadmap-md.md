---
title: 001-ebd_learn_roadmap.md
date: 2023-05-02 14:35:20
tags:
---
# 嵌入式基础必备知识

## C语言基础

三大语法结构、常用的数据类型、函数、结构体、指针、文件操作

## 数据结构

数组、队列、链表、堆栈、树、图、散列表等  

## 计算机原理

数据表示和运算、存储系统、指令系统、总线系统、中央处理器、输入输出系统等  

## 操作系统

进程管理、内存管理、文件管理、输入输出管理等  

## 硬件基础知识

电路基础知识、数电模电基础知识、常用的电子元器件等  

# CPU

## 单片机

51单片机
软件：认识单片机、熟悉逻辑运算、点亮一颗LED灯、按键检测、串口通信、定时器、中断
硬件：电阻元器件了解，基本模块电路了解，时钟电路，尝试绘制51单片机原理图和PCB

## ARM处理器

STM32
● 基础练习
 主要练习：点亮LED灯、GPIO的输入输出操作、中断操作、UART通信、IIC通信等  
● 进阶练习
 主要练习：DMA通信、SPI通信、CAN通信、LCD显示屏，ADC等  
● 高阶练习
 主要学习：STM32时钟架构、总线架构、电源管理、代码框架、SDIO通信、USB通信等。  
● 学习建议及资料
STM32会有寄存器和库函数两个版本，建议交叉学习，理解会更加深刻推荐正点原子、野火的STM32F103或者STM32F407系列  
Cortex-M
Cortex-R
Cortex-A
Zynq7020
ZYNQ领航者V2开发板 http://www.openedv.com/docs/boards/fpga/zdyz_linhanz(V2).html
RK3288
https://www.t-firefly.com/product/rk3288.html
RK3399
https://www.t-firefly.com/product/rk3399.html
香橙派http://www.orangepi.cn/html/hardWare/computerAndMicrocontrollers/index.html

http://www.orangepi.cn/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-R1-Plus-LTS.html

# 硬件通信接口

UART
TTL、RS232/RS485/RS422
I2C
SPI/QPSI
ADC
PWM
CAN/CANFD
USB
ethernet
PCI/PCIE

# RTOS

 RTOS，实时操作系统，可以理解为STM32与Linux之间的桥梁，由于其实现思想大都取之于Linux，所以也称之为精简版的Linux。
 常用的实时操作系统有：UCOS，VxWork，FreeRTOS，RT-Thread

移植RTOS系统、多任务管理、调度算法、消息队列、信号量互斥量、事件、内存管理等。  
FreeRTOS
● FreeRTOS官网https://www.freertos.org/
● FreeRTOS github源码
 FreeRTOS(TM) is a market leading RTOS from Amazon Web Services  ，包括FreeRTOS的所有工程
https://github.com/freertos

FreeRTOS的工程源码，包括demo和kernel【submodule】
https://github.com/FreeRTOS/FreeRTOS

FreeRTOS kernel源码
https://github.com/FreeRTOS/FreeRTOS-Kernel

发布的demo和kernel一起的源码版本
https://github.com/FreeRTOS/FreeRTOS/releases

● 欢迎阅读韦东山百问网freeRTOS教程！    http://rtos.100ask.org/freeRTOS%E6%95%99%E7%A8%8B/index.htmlhttps://www.bilibili.com/video/BV1844y1g7ud?p=1

# Linux

包括Linux基础篇，Linux开发
Linux开发又分为应用开发，驱动开发，内核开发

## Linux基础篇

Linux常用命令、VIM学习、Linux的Shell编程、GCC编译、Makefile等  

## 应用开发

嵌入式linux应用编程、存储、网络管理、QT编程、TCP/IP协议、HTTP协议等  

## 驱动开发

内核模块编译原理、字符设备驱动框架、平台设备驱动、设备树、Pinctrl子系统、I2C子系统、中断子系统、块设备驱动框架、Bootloader等  

## 内核开发

系统调用、存储管理、进程管理、内存管理、文件管理等
