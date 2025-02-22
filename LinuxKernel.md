### Understanding Linux Kernel

There are multiple good books on understanding Linux Kernels.
Linux kernels contain multiple parts. filesystems, I/O, memory, process, and many others. One can think of linux kernel as an API to the physical hardware underneath, as
one dealing with physical hardware is pretty difficult.

The following are the list of books to get started.

* [Linux Device Drivers: Where the Kernel Meets the Hardware]  (https://amazon.ca/Linux-Device-Drivers-Kernel-Hardware/dp/0596005903) 
* The Linux Programming Interface: A Linux and UNIX System Programming Handbook
* Understanding Linux Network Internals: Guided Tour to Networking on Linux
* Linux Kernel Development
* Understanding the Linux Kernel
* Professional Linux Kernel Architecture
* User Mode Linux
* Intel V3 Intel 64 and IA-32 Architectures Software Developer’s Manual Volume 3
* [Linux insides](https://github.com/0xAX/linux-insides) This is an education site of the Linux kernel 


Caveat.  When one is reading the books mentioned above, one need to keep in mind the Linux kernel version it is written against.  Linux kernel are always been updated to support new hardware, fixing bugs, or new way to control and administer the underlying hardware.  Therefore, use the book as an introduction to the underlying concepts, and read the code for understanding.

Another good place for information is the doc directory in the Linux kernel.  It provide a lot of information, and latest changes to the code change.


Comparison to other operating systems
Linux Kernel is different from Windows Kernel, Apple MacOS, and the FreeBSD, as all of them had different designs.



### Kernel parameters
This provides some notes on passing the video modes. 

* https://www.systutorials.com/configuration-of-linux-kernel-video-mode/
* https://linuxhint.com/set_screen_resolution_linux_kernel_boot/


### Profiling source code in Linux
* https://stackoverflow.com/questions/375913/how-can-i-profile-c-code-running-on-linux


#### OS lectures
https://courses.cs.washington.edu/courses/cse451/12sp/lectures.html


### redirect the port numbers
redir --lport 3389 --caddr=GuestIP --cport 3389
