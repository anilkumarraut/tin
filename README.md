NilDis - A Minimal Linux Distribution Builder
NilDis is a lightweight shell script that simplifies the creation of a complete, minimal Linux distribution using BusyBox. The script compiles the Linux kernel 5.16.19 alongside BusyBox 1.34.1, resulting in a compact operating system that requires just 70 MB of RAM and 40 MB of storage. It’s perfect for resource-constrained devices and runs on minimal Debian- or Ubuntu-based systems that match the architecture of the target hardware.

Why Choose NilDis?
NilDis stands out as an approachable tool for anyone looking to build a Linux system from scratch. Whether you’re a beginner or an experienced developer, it takes the complexity out of creating your own minimal Linux environment.

Easy Setup: Works with VirtualBox, Hyper-V, and KVM/QEMU (excluding VirtIO drives).
Quick and Efficient: Just a few adjustments to the script, and you’ll have a functioning Linux system in minutes.
Beginner-Friendly: Easier to use compared to tools like Buildroot, Aboriginal, mkroot, or Linux From Scratch.

What NilDis Does
Installs essential libraries and dependencies for building Linux.
Downloads and compiles BusyBox and the Linux kernel using default options.
Creates a set of minimal scripts to streamline system management.
Installs the system onto the specified drive (virtual or physical).
With just a few edits to the nildis.sh script, you can personalize the build to suit your needs. After confirming the setup, you can sit back and let the script do all the work—within minutes, your minimal Linux system will be ready to use.

Note: NilDis overwrites the target drive completely, so make sure to back up any important data beforehand.

Built-In Features
Out of the box, NilDis supports:

Networking with ifupdown and DHCP.
Basic system logging (syslogd).
Minimalistic startup scripts and cron jobs.
A lightweight HTTP server (httpd), FTP server (ftpd), and telnet service.
The distribution can run on any device that supports the architecture for which it was built, making it flexible for a variety of use cases.

