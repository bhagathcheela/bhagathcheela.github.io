---
layout: default
title: "Projects"
permalink: /projects/
---

# Computer Architecture & Accelerators

## LC4 Processor Design using Xilinx Zynq -7000 SoC
<img width="268" height="200" style="float: left" src="https://user-images.githubusercontent.com/47292036/175859921-fea6bfd6-0c09-430d-9d0c-4227c8a38c2c.jpg">

- Implemented a 5 staged pipelined, superscalar LC4 processor using Verilog in Xilinx Zynq 7000 SoC
- Performed bypassing to handle the data hazards, optimized the pipelines to close the timing requirement at 66 MHz

## Deduplication and Compression using Xilinx Zynq MPSoC

<img width="192" height="144" style="float: right" src="https://user-images.githubusercontent.com/47292036/175859980-75bcda94-91a7-4e56-bd91-3ffd7bb17e9a.jpg">

- Developed a compressor to receive data in real time and compress into memory using deduplication and compression
- Implemented a 5-stage pipeline for deduplication to run on the multiple ARM CPU cores using NEON intrinsics
- Accelerated the compression algorithm and achieved a throughput of 48 Mbps using on-chip FPGA

## Hardware Accelerator for Machine Learning using FPGAs

<img src="https://user-images.githubusercontent.com/47292036/175862594-f177f116-2229-47cd-8401-d7eb089854c4.png">

- Devised an FPGA-accelerated convolutional layer for accelerating DCNN using AWS F1 instance
- Integrated the kernel into Pytorch using C++ extensions and built the host code using OpenCL API
- Explored the design space using multiple kernels and out of order queue techniques to achieve comparable speed up with single core CPU

## Automated Optical Inspection for PCB’s using Machine Learning

<img width="235" height="214" style="float: right; padding-left: 10px" src="https://user-images.githubusercontent.com/47292036/175860038-4d04849b-219d-43f8-9d7b-6be14443564b.jpg">

- Developed a method to identify missing components on a PCB using Machine Learning and accomplished an accuracy of 86%
- Fine-tuned the features and evaluated the performance on various CNNs including ResNet, VGG and Inceptionv3


<!-- ![99073](https://user-images.githubusercontent.com/47292036/175859851-11afc153-377d-4a8e-a4da-9dda6c7eed88.jpg) -->


<!-- ![Picture1](https://user-images.githubusercontent.com/47292036/175860086-a3a01d41-7010-436b-8c96-de2ff4804332.jpg) -->

<!-- ![three-kernel-highlight2](https://user-images.githubusercontent.com/47292036/175860285-6b71b7ab-fa65-4157-bf95-f9bddb437a13.png) -->

<!-- ![zcu102_2](https://user-images.githubusercontent.com/47292036/175860133-650a26a8-3668-42e5-aedf-c38f9001dbbc.jpg) -->

<!-- Transmitter & Receiver Chain Design using ADS

- Designed RF transmitter chain consisting of SSA, PA at 7 GHz with a gain of 24 dB and PAE of 25% using Keysight ADS
- Realized LNA with a noise figure of 1.34 dB and gain of 7 dB at 7 GHz, direction coupler with insertion loss less than 0.4 dB and 10 dB coupling using Keysight ADS and AWR -->

# Embedded Electronics
## [Smart Watch](https://devpost.com/software/protowatch-smart-device-on-your-wrist-that-also-tells-time)

<img width="1037" height="691" align="center" src="https://user-images.githubusercontent.com/47292036/175863845-760fd3b8-ea23-41be-817d-3cd7fe1b2b40.jpg">

- Designed a smart watch with LCD display that can update task list along with date, time, temperature and IMU measurement
- Integrated Ambient light sensor for automatic brightness control and IMU to measure to update the step count
- Developed the firmware using FreeRTOS with OTA firmware upgrade capability and using on-chip memory resources.

## [Nano-Satellite](https://parikshit.space/)

<img src="https://user-images.githubusercontent.com/47292036/175864687-cc297a71-b71f-4134-a98e-2499838ff5d4.jpg" style="float: center">

- Designed a smart watch with LCD display that can update task list along with date, time, temperature and IMU measurement
- Integrated Ambient light sensor for automatic brightness control and IMU to measure to update the step count
- Developed the firmware using FreeRTOS with OTA firmware upgrade capability and using on-chip memory resources.
