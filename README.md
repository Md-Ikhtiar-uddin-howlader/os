#Tutorial to deploy a complete Apache, PHP,MYSQL and PHPMYADMIN service on windows

<p align="center">
![IIUM Logo](/images/IIUM_LOGO.png)


##CSCI 3300 Section 02 OPERATING SYSTEMS

**PREPARED BY:**
Name 	Matric No
Md Ikhtiar Uddin Howlader 	1834619
Rasel Ahmed	1836247
Mohammad Sazidur Rahman	1835197
</p>

###1. Introduction:
An operating system is a piece of software that connects the user to the computer hardware. After being loaded into a computer by a boot software, it is the programme that administers all of the other application programmes in the computer. Users may interact with the OS using a command line interface (CLI) or a graphical user interface (GUI), which is often done with a keyboard, mouse, or touchscreen. An operating system is very useful for computer software and software development. Without an operating system, each programme would need its own user interface as well as the considerable code necessary to manage all of the underlying computer's low-level tasks, such as disc storage, network connections, and so on.

###2. Docker:
Docker is basically a software development platform and a sort of virtualization technology that enables us to create and deploy programmes inside neat virtual containerized environments. It implies that applications behave the same regardless of where they are or what system they are running on. Docker containers may be deployed to practically any computer without introducing compatibility issues, guaranteeing that your software stays system agnostic, making it easy to use, build, maintain, and deploy. Docker is intended to give a rapid and lightweight environment in which code can be executed quickly, as well as an extra facility of the competent work process to remove code from the computer for testing before production.
Unlike a virtual machine, Docker is a sort of virtualization in which resources are shared directly with the host. This allows us to construct containers and operate several Docker containers in situations where we would only be able to host a few virtual machines. A virtual machine must set aside a particular amount of resources, such as HDD space, memory, and processing power, mimic hardware, and boot a whole operating system before connecting with the host computer through a tarator programme called a "Hypervisor" that runs on the host operating system. Docker links directly to the system kernel on Linux systems, as well as Windows 10 and Windows Server 2016 and later. This implies that any version of Linux may be run natively in a container. Not only that, but Docker uses less disc space since it uses a tiered file system to effectively reuse data.

###3. Required Installation steps and procedures:
