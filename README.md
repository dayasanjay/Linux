### Linux

## <b>What is Linux?</b>

Just like Windows, iOS, and Mac OS, Linux is an operating system. In fact, one of the most popular platforms on the planet, Android, is powered by the Linux operating system. An operating system is software that manages all of the hardware resources associated with your desktop or laptop.

### <b>Description of Linux</b>

### The Linux operating system comprises several different pieces:

<b>1.Bootloader –</b>  The software that manages the boot process of your computer. For most users, this will simply be a splash screen that pops up and eventually goes away to boot into the operating system.<br>
<b>2.Kernel –</b> This is the one piece of the whole that is actually called ?Linux?. The kernel is the core of the system and manages the CPU, memory, and peripheral devices. The kernel is the lowest level of the OS.<br>
<b>3.Init system </b> – This is a sub-system that bootstraps the user space and is charged with controlling daemons. One of the most widely used init systems is systemd? which also happens to be one of the most controversial. It is the init system that manages the boot process, once the initial booting is handed over from the bootloader (i.e., GRUB or GRand Unified Bootloader).<br>
<b>4.Daemons –</b> These are background services (printing, sound, scheduling, etc.) that either start up during boot or after you log into the desktop.<br>
<b>5.Graphical server –</b> This is the sub-system that displays the graphics on your monitor. It is commonly referred to as the X server or just X.<br>
<b>6.Desktop environment –</b> This is the piece that the users actually interact with. There are many desktop environments to choose from (GNOME, Cinnamon, Mate, Pantheon, Enlightenment, KDE, Xfce, etc.). Each desktop environment includes built-in applications (such as file managers, configuration tools, web browsers, and games).<br>
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

<b>Popular Linux distributions include:</b><br>
LINUX MINT<br>
MANJARO<br>
DEBIAN<br>
UBUNTU<br>
ANTERGOS<br>
SOLUS<br>
FEDORA<br>
ELEMENTARY OS<br>
OPENSUSE

### Linux file system overview

Linux has hierarchical tree structue means it has only one root folder whereas windows has multiple root folders.

<b>/root</b>                 ----> Root users home directory is at /root<br>
<b>/home</b>                 ----> For normal users<br>
<b>/bin</b>                  ----> Excecutables or most essential user commands<br>
<b>/sbin</b>                 ----> System relevant commands used by super user<br>
<b>/lib</b>                  ----> Essential shared libraries that executables from /bin or /sbin use<br>
<b>/user</b>                  ----> This is used for user home directories(because of storage limitations it was split into to root binary folders and user binary folders)<br>
<b>/user/local</b>           ----> Programs that you install on the computer and third party applications like docker,minicube,java etc<br>
<b>/opt</b>                  ----> Third party programs you install<br>
<b>/boot</b>                  ----> Contains files requored for booting<br>
<b>/etc</b>                   ----> Place where configurations for system wide applications is stored<br>
<b>/dev</b>                  ----> Location of device files like webcam keyboard, hard drive etc<br>
<b>/var</b>                  ----> Contains files to which the system writes data during the course of its operation<br>
<b>/var/log</b>              ----> Contains log files<br>
<b>/var/cache</b>             ----> Contains cached data from application programs<br>
<b>/tmp</b>                  ----> Temporary resources required for some process, kept here temporarily<br>
<b>/media</b>                ----> Contains subdirecories where removable media device inserted into the computer are mounted<br>
<b>/mnt</b>                  ----> Historically system admins mounted temporary file systems there<br>
### Use Command Line Interface (CLI) Over Graphical User Interface (GUI)
<b>why using CLI instead GUI</b><br>
1.work more efficient<br>
2.Easier for bulk operations<br>
3.CLI is more powerful<br>
4.Virtual tasks like video editing<br>

### Linux Accounts and Groups
<b>Basically there are three user categories</b><br>

<b>1.Super user account</b><br>
   * Root user has unrestricted permissions<br>
   * For adminstrative tasks need to login as root user or excecute commands as root using the command 'sudo' <br>

<b>2.Regular/standard user account</b><br>
   * Aregular user we creae to login. e.g : tom ---> /home/tom<br>

<b>3.Service account</b><br>
   * Relevant for linux server distros. e.g Apache, MYSQL<br>
   * Each service will get its own user. e.g : mysql user will start mysql application<br>
   * Best practice for security<br>
 
### Basic Linux Commands
<b> The commands which we use in our command prompt</b><br>
<b>pwd</b>  nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         ----> shows the present directory<br>
<b>ls</b>            ----> shows the list of files and directories<br>
<b>ls -a</b>         ----> shows the list of files and directories including hidden files and directories<br>
<b>cd</b>            ----> Use the command to go to a directory<br>

 
