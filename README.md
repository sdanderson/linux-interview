Linux Administration interview questions
======

## Simple Linux Questions:

* What is the name and the UID of the administrator user?
* How to list all files, including hidden one, in a directory?
* What is the Unix/Linux command to remove a directory and its contents?
* Which command will show you free/used memory? Does free memory exist on Linux?
* How to connect to a remote server or what is SSH?
* I get "command not found" for ```ifconfig -a```. What can be wrong?
* What command will show the available disk space on the Unix/Linux system?
* What Unix/Linux commands will alter a files ownership, files permissions?
* What does ```chmod +x FILENAME```do?
* What does the permission 0750 on a file mean?
* What does the permission 0750 on a directory mean?
* How to redirect STDOUT and STDERR in bash? (> /dev/null 2>&1)
* What is the difference between UNIX and Linux
* What is the difference between Telnet and SSH?
* Explain the three load averages and what do they indicate


## Medium Linux Questions:

* What is a packet filter and how does it work?
* What is swap and what is it used for?
* What is an A record, an NS record, a PTR record, a CNAME record, an MX record?
* Are there any other RRs and what are they used for?
* What is the sticky bit?
* What is an inode and what fields are stored in an inode?
* What is a runlevel and how to get the current runlevel?
* What is SSH port forwarding?
* Describe a scenario when you get a "filesystem is full" error, but 'df' shows there is free space.
* Describe a scenario when deleting a file, but 'df' not showing the space being freed.
* What happens to a child process that dies and has no parent process to wait for it and what’s bad about this?
* How to know which process listens on a specific port?
* What is Iptables?
* Which privilege is required to operate iptables?
* How can you find all the regular files in a directory?
* What is LVM?
* Which command is used to extend a logical volume?
* Tell me the steps to remove the swap file?
* What is the role of /etc/resolv.conf file?
* What daemon is responsible for tracking events on your system?

## Hard Linux Questions:

* What shortcuts do you use on a regular basis?
* What kind of keys are in ~/.ssh/authorized_keys and what it is this file used for?
* I've added my public ssh key into authorized_keys but I'm still getting a password prompt, what can be wrong?
* Did you ever create RPM's, DEB's or solaris pkg's?
* What's happening when the Linux kernel is starting the OOM killer, how does it choose which process to kill first.
* Describe the linux boot process with as much detail as possible, starting from when the system is powered on and ending when you get a prompt.
* When trying to umount a directory it says it's busy, how to find out which PID holds the directory?
* How do you debug a running process or a library that is being called? A: strace -p PID
* What are the steps to create LVM logical volume?

## Java Administration

* What is the JVM?
* Describe garbage collection.
* What are the types of garbage collectors?
* Walk me through a garbage collection, what happens?
* What are the heap generations?
* Describe the young heap spaces.
* What is stored in the To space of a young generation 
* How do you set the heap size?


## Apache

* What is the basic directory structure?
* What files are contained in /etc/httpd/conf.d?
* What is virtual hosting?
* What are the types of virtual hosts?
* What is meaning of "Listen" in httpd.conf file?
* What is DocumentRoot?
* Can I serve content out of a directory other than the DocumentRoot directory?
* Which tool you have used for Apache benchmarking?
* You are getting following codes (2xx, 3xx, 4xx, 5xx) in Apache, at some point of time. What does this means?
* Can we have two Apache Web servers on a single machine?
* Which of the following best explains why Apache Web servers are able to handles multiple requests? A. Apache is able to spawn child processes that handle requests before they die.
* What does DSO stands for?

## Redhat

* What is RPM?
* What is YUM?
* Explain the differences.
* What does /boot directory contains?
* What does /dev directory contain?
* If you are getting error "package is already installed" but you have to install package any how. what option you will use?
* How to install Linux software’s by RPM?
* How Many Run Levels present in Linux?
	* 0: Halt the system
	* 1: Single-user mode 
	* 2: Not used
	* 3: Multi-user mode with text login
	* 4: Not used
	* 5: Multi-user mode with graphical login
	* 6: Reboot
* What is the default runlevel for a server?
* Explain /proc filesystem?

## Puppet

* What is Puppet?
* What is Manifests?
* What is Module and How it is different from Manifest?
* What is Facter?

## Shell

* What does . mean in regular expressions?
* What is difference between ” and ‘?
* What does $? give you?



## Other Great References:

Some questions are 'borrowed' from other great references like:

* https://github.com/chassing/linux-sysadmin-interview-questions
* http://www.masteringinlinux.com/linux-questions/apache-interview-questions-answers.html
* http://www.nextstep4it.com/qa/system_admininstration/linux/