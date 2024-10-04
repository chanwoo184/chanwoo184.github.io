---
title: Verifying VPC Connection Setup via GNS3
tags:
    - nw
date: 2024-08-29
---

A basic setup exercise for practicing computer network environments from a software developer's perspective.

<!--more-->

- First, install the VM and GNS3 VM, then connect them to GNS3. 
• VM (Virtual Machine): A program that creates a specific HW/SW environment, even without the actual hardware. For example, if your computer runs Windows/x86, but you need to run a program on Linux/ARM, one way is to buy the necessary HW/SW. However, if that is not feasible, you can use VM software to virtualize the required environment and run it.

- After creating the GNS3 project, select "VPCS" from End Devices, drag and drop it, then click "Add a link" and link the two PCs. Finally, click the Start button at the top to run the simulation.

- Click the console button for each PC and enter the following commands:

PC1> ip 10.1.1.1 255.255.255.0 10.1.1.254

PC2> ip 10.1.1.2 255.255.255.0 10.1.1.254

PC1> ping 10.1.1.2

If the ping appears successfully as shown in the image, then the setup is successful.

**Learn more!** ==> https://blog.naver.com/dlacksdn86
