# weenix

As a semester-long project for CSCI1690, I built out a full Unix-based operating system kernel.

The project involved implementing the following:
1) Procs — Threads, processes, and synchronization primitives.
2) Drivers — Device drivers for terminals, disks, and the memory devices */dev/zero* and */dev/null*.
3) VFS — An interface between the operating system kernel and the various file systems (such as S5FS or RAMFS).
4) S5FS — A file system based on the original Unix file system.
5) VM — Userspace address space management, running user-level code, servicing system calls, and basically everything else needed to combine all of the previous componenets into a fully functioning operating system. This includes virtual memory maps, handling page faults, memory management via anonymous objects and shadow objects, and system calls.

NOTE: This is a placeholder repo with no code to respect Brown's Academic Code
