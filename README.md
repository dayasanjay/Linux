### Linux

## What is Linux?

Just like Windows, iOS, and Mac OS, Linux is an operating system. In fact, one of the most popular platforms on the planet, Android, is powered by the Linux operating system. An operating system is software that manages all of the hardware resources associated with your desktop or laptop.

### Description of Linux

<b>The Linux operating system comprises several different pieces:</b>

<b>1.Bootloader –</b>  The software that manages the boot process of your computer. For most users, this will simply be a splash screen that pops up and eventually goes away to boot into the operating system.
<b>2.Kernel –</b> This is the one piece of the whole that is actually called ?Linux?. The kernel is the core of the system and manages the CPU, memory, and peripheral devices. The kernel is the lowest level of the OS.
<b>3.Init system </b> – This is a sub-system that bootstraps the user space and is charged with controlling daemons. One of the most widely used init systems is systemd? which also happens to be one of the most controversial. It is the init system that manages the boot process, once the initial booting is handed over from the bootloader (i.e., GRUB or GRand Unified Bootloader).
<b>4.Daemons –</b> These are background services (printing, sound, scheduling, etc.) that either start up during boot or after you log into the desktop.
<b>5.Graphical server –</b> This is the sub-system that displays the graphics on your monitor. It is commonly referred to as the X server or just X.
<b>6.Desktop environment –</b> This is the piece that the users actually interact with. There are many desktop environments to choose from (GNOME, Cinnamon, Mate, Pantheon, Enlightenment, KDE, Xfce, etc.). Each desktop environment includes built-in applications (such as file managers, configuration tools, web browsers, and games).
<b>7.Applications –</b> Desktop environments do not offer the full array of apps. Just like Windows and macOS, Linux offers thousands upon thousands of high-quality software titles that can be easily found and installed. Most modern Linux distributions (more on this below) include App Store-like tools that centralize and simplify application installation. For example, Ubuntu Linux has the Ubuntu Software Center (a rebrand of GNOME Software? Figure 1) which allows you to quickly search among the thousands of apps and install them from one centralized location.

### Why use Linux?

This is the one question that most people ask. Why bother learning a completely different computing environment, when the operating system that ships with most desktops, laptops, and servers works just fine?

To answer that question, I would pose another question. Does that operating system you?re currently using really work ?just fine?? Or, do you find yourself battling obstacles like viruses, malware, slow downs, crashes, costly repairs, and licensing fees?
If you struggle with the above, Linux might be the perfect platform for you. Linux has evolved into one of the most reliable computer ecosystems on the planet. Combine that reliability with zero cost of entry and you have the perfect solution for a desktop platform.

That’s right, zero cost of entry… as in free. You can install Linux on as many computers as you like without paying a cent for software or server licensing.

Linux is also an open source license. Open source follows these key tenants:

The freedom to run the program, for any purpose.
The freedom to study how the program works, and change it to make it do what you wish.
The freedom to redistribute copies so you can help your neighbor.
The freedom to distribute copies of your modified versions to others.
These points are crucial to understanding the community that works together to create the Linux platform. Without a doubt, Linux is an operating system that is ?by the people, for the people?. These tenants are also a main factor in why many people choose Linux. It?s about freedom and freedom of use and freedom of choice.

### Linux Distributions

Linux has a number of different versions to suit any type of user. From new users to hard-core users, you’ll find a “flavor” of Linux to match your needs. These versions are called distributions (or, in the short form, “distros”). Nearly every distribution of Linux can be downloaded for free, burned onto disk (or USB thumb drive), and installed (on as many machines as you like).

<>bPopular Linux distributions include:</b>
LINUX MINT
MANJARO
DEBIAN
UBUNTU
ANTERGOS
SOLUS
FEDORA
ELEMENTARY OS
OPENSUSE

### Linux file system overview

Linux has hierarchical tree structue means it has only one root folder whereas windows has multiple root folders.

<b>/root</b>                 ----> Root users home directory is at /root
<b>/home</b>                 ----> For normal users
<b>/bin</b>                  ----> Excecutables or most essential user commands
<b>/sbin</b>                 ----> System relevant commands used by super user
<b>/lib</b>                  ----> Essential shared libraries that executables from /bin or /sbin use
<b>user</b>                  ----> This is used for user home directories(because of storage limitations it was split into to root binary folders and user binary folders)
<b>/user/local</b>           ----> Programs that you install on the computer and third party applications like docker,minicube,java etc
<b>/opt</b>                  ----> Third party programs you install
