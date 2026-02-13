### Obtaining Phone Spec's

Whatever Android Phone you choose to flash (or install on the chip) with a custom rom, you need to obtain the phone's hardware specifications in order to install the correct components.

## Device tree

A device tree is a hierarchical data structure (a tree of nodes and properties) used in operating systems, particularly Linux, to describe physical hardware components—such as CPU, memory, and peripherals—that cannot be automatically detected at boot. It decouples hardware description from the kernel, enabling the same kernel to support diverse embedded hardware. 

The Device Manager in Windows would be considered a Device Tree.

Key details about Linux / Android device trees:

Structure & Format: Represented in text files as Device Tree Source (.dts) or included files (.dtsi), then compiled into a binary Device Tree Blob (.dtb).

Nodes & Properties: Nodes represent devices (e.g., interrupt controllers, GPIOs), while properties are key-value pairs defining attributes like address, interrupts, and speed.

Components: The root node (/) defines the machine model, while compatible strings allow the OS to match device drivers to the hardware.

Usage: The bootloader loads the .dtb file into memory and passes it to the operating system during boot, allowing the kernel to know what hardware exists and how to configure it.

Purpose: Primarily used in Android, ARM, PowerPC, and other embedded systems to avoid hardcoding board-specific hardware details into the kernel binary.


Android is built on a modified Linux kernel, making it a Linux-based operating system, but it's a highly customized stack with its own runtime (Android Run Time - ART) and frameworks, differing significantly from traditional desktop Linux distributions like Ubuntu or Fedora. While it uses the Linux kernel for core functions like memory management and process scheduling, Android's user-space environment (apps, system services, UI) is unique, using Java/Kotlin for apps rather than typical GNU tools. So in one sense Android is not a Linux distro like Ubuntu or Fedora but is a high-level OS that sits on a low-level OS, which is almost always Linux.


https://source.android.com/docs/core/architecture/dto

https://source.android.com/docs/core/architecture/bootloader/dtb-images

https://brandolamarck.substack.com/p/how-to-extract-and-decompile-the

https://derpfest.org/build

https://gist.github.com/mvaisakh/1a45694e33584592e8fae37fe29d757d

https://xdaforums.com/t/how-to-convert-back-qualcomms-dtb-to-dts-file-extract-kernel-config.3221223/

https://xdaforums.com/t/rom-wt88047-l-5-1-1-cyanogenmod-unofficial-builds.3200883/

https://github.com/moetayuko/split-appended-dtb

https://discourse.coreelec.org/t/extracting-dtb-file-from-a-running-android-os/1218

https://wiki.postmarketos.org/wiki/Device_Tree_(dtb)

