# xv6--lsof-system-call
add a new system call to the xv6 operating system.

we will add a command called lsof that will print the list of open files for all running processes.
the change is in the following files:
- syscall.h
- defs.h
- user.h
- sysproc.c
- usys.S
- syscall.c
- proc.c
- lsof.c
