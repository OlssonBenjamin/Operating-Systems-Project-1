# Operating-Systems-Project-1
In this project, I implemented a system call in Reptilian along with three static library functions that
allow the system call to be invoked from a C API. These custom system calls get and set a custom
process log level that sits atop the standard Linux kernel’s diagnostic message logging system
(dmesg) and allows processes to submit log entries along with a log level. If the log level for the message
is more severe (lower than) the current log level, the message is added to the kernel log. Log levels
and names will correspond to those in the Linux kernel. 
