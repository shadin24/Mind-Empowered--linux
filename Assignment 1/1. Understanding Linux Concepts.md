# 1. Understanding Linux Concepts:
## Evolution of Unix
In 1969, a team of developers of Bell Labs started a project to make a common software for all the computers and named it as 'Unix'. It was simple and elegant, 
used 'C' language instead of assembly language and its code was recyclable. As it was recyclable, a part of its code now commonly called 'kernel' was used to 
develop the operating system and other functions and could be used on different systems. Also its source code was open source.
## Evolution of Linux
In 1991, Linus Torvalds a student at the university of Helsinki, Finland, thought to have a freely available academic version of Unix started writing its own code.
Later this project became the Linux kernel. He wrote this program specially for his own PC as he wanted to use Unix 386 Intel computer but couldn't afford it. He 
did it on MINIX using GNU C compiler. GNU C compiler is still the main choice to compile Linux code but other compilers are also used like Intel C compiler.

He started it just for fun but ended up with such a large project. Firstly he wanted to name it as 'Freax' but later it became 'Linux'.He published the Linux kernel 
under his own license and was restricted to use as commercially. Linux uses most of its tools from GNU software and are under GNU copyright. In 1992, he released the 
kernel under GNU General Public License.

## Linux Components
1.Linux Kernel: The core component of Linux, responsible for managing system resources, providing device drivers, and facilitating communication between hardware 
and software.

2.Shell: The command-line interface (CLI) or shell is a program that allows users to interact with the operating system by typing commands. Common shells include
Bash (Bourne Again Shell) and Zsh (Z Shell).

3.GNU Core Utilities: A collection of essential command-line utilities provided by the GNU project. These utilities include commands like ls (list directory
contents), cp (copy files), mv (move files), and rm (remove files).

4.File System: Linux supports various file systems such as ext4, XFS, Btrfs, and more. The file system organizes and manages the files and directories on storage 
devices.

5.Package Management System: Linux distributions typically have a package management system that allows users to install, update, and remove software packages.
Examples include APT (Advanced Package Tool) used in Debian-based distributions and YUM (Yellowdog Updater, Modified) used in Red Hat-based distributions.

6.Graphical Server: Linux can provide a graphical user interface (GUI) through a graphical server, such as X11 or Wayland. The server manages graphical display 
output and input from devices like keyboards and mice.

7.Window Manager/Desktop Environment: A window manager controls the placement and appearance of windows on the screen, while a desktop environment provides a 
complete user interface with additional features like panels, menus, and system settings. Popular window managers include Xfwm, Openbox, and i3, while popular 
desktop environments include GNOME, KDE Plasma, and Xfce.

8.Libraries: Linux provides a wide range of software libraries that programmers can use to develop applications. These libraries include the GNU C Library (glibc) 
and various language-specific libraries like GTK (GIMP Toolkit) for GUI applications.

9.Networking Components: Linux includes networking components that enable network connectivity and communication. These components include network drivers,
protocols (TCP/IP, UDP), network utilities (ifconfig, ip), and services like the Domain Name System (DNS) resolver.

10System Initialization: Linux systems typically use an initialization system, such as systemd or init, to manage the boot process and start and stop system 
services.

## Differences between Linux and other popular operating systems
1.Licensing: Linux is an open-source operating system, which means that it can be freely used, modified, and distributed by anyone. Windows and macOS are both
proprietary operating systems, which means that they are owned and controlled by their respective companies, Microsoft and Apple.

2.User Interface: Linux offers a wide range of graphical user interfaces (GUIs) that can be customized to suit individual preferences. In contrast, Windows and 
macOS have a fixed user interface that cannot be significantly customized.

3.Software Availability: Windows and macOS have a wider selection of software available to them, including popular commercial software like Microsoft Office and
Adobe Creative Suite. However, Linux has a vast repository of open-source software, and many popular commercial applications have Linux versions or alternatives.

4.Hardware Support: Windows and macOS are more widely supported by hardware manufacturers than Linux. As a result, users may have difficulty finding Linux drivers
or support for some hardware devices.

5.Security: Linux is generally considered more secure than Windows or macOS due to its open-source nature, which allows for more frequent and rigorous security 
audits. Additionally, Linux has a reputation for being less vulnerable to viruses and malware than Windows.

6.Performance: Linux is often preferred for its performance capabilities. It is known for being lightweight and fast, making it an ideal choice for servers and 
embedded systems. Windows and macOS, on the other hand, are typically more resource-intensive.


7.Cost: Linux is generally free to use, whereas Windows and macOS are proprietary and come with a cost. Additionally, Linux's open-source nature makes it more 
accessible to those who want to modify or customize the operating system to their liking.

## Linux file hierarchy and directory structure.

![Screenshot from 2023-05-17 16-49-04](https://github.com/shadin24/Mind-Empowered--linux/assets/94816647/a6faf1d6-c6a0-4448-a352-95685bf5b606)

These are the common top-level directories associated with the root directory:
<br> /bin – binary or executable programs.
<br> /etc – system configuration files.
<br> /home – home directory. It is the default current directory.
<br> /opt – optional or third-party software.
<br> /tmp – temporary space, typically cleared on reboot.
<br> /usr – User related programs.
<br> /var – log files.


