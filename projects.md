---
layout: page
title: Projects
permalink: /projects/
---

## Personal Projects:

### PanicOS - [Link](https://github.com/JasonBrave/PanicOS)
![](/images/projects/PanicOS.png)
- A simple x86 operating system with graphical user space
- Kernel features: BIOS/UEFI booting, SMP, Loadable kernel modules, FAT32 filesystem, Hardware abstraction layer
- Device Support: PCI/PCIe, USB with UHCI controller, IDE/ATA, virtio devices
- User space: Dynamic linking, Graphical desktop envoironment, C and C++ standard library, C++ GUI widget toolkit

## Group Projects:

### RobotLog - [Link](https://github.com/FRC6854/RobotLog)
![](/images/projects/RobotLog.png)
- FRC(FIRST Robotics Competition) Robot path planning and replay tool developed for [FRC Team 6854 - Viking Robotics](https://github.com/FRC6854)
- Implemented with C++ using GTKmm and Cairo library

Features:
- Read robot motor encoder telemetry CSV file and replay robot trajectory
- User can sketch planned robot path on the user interface and export coordinates to CSV file
- User can deploy path directly to RobotRIO, by RobotLog invoking `sftp` command
- Runs on GNU/Linux and Windows(with MSYS2).
