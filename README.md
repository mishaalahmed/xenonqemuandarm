# XEN on QEMU & ARM64
This repository aims to walk you through the process of setting up Xen for Arm using the Qemu emulator. 
If you are using x32/64 on your Host PC. You may encounter some errors. I have provided the possible error that can occur and solutions to the problems.

To achieve this, follow these steps:
<ul>
Install Qemu for arm64 by downloading and setting it up.
Configure settings for Linux Dom0 and Linux DomU.
Acquire and build the arm64 toolchain.
Cross-compile the Linux Dom0 image.
Cross-compile the Linux DomU image.
Compile Xen and Xen-tools.
Execute the Dom0 image and launch the DomU image from Dom0.
</ul>

Reference
<ul>
<b> https://wiki.xenproject.org/wiki/Xen_ARM_with_Virtualization_Extensions/qemu-system-aarch64. </b> 
</ul>


