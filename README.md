# Trapfetch

### Linux kernel

There are several guides for kernel developers and users. These guides can 
be rendered in a number of formats, like HTML and PDF. Please read
Documentation/admin-guide/README.rst first.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.  The formatted documentation can also be read online at: 

    https://www.kernel.org/doc/html/latest/

There are various text files in the Documentation/ subdirectory,
several of them using the Restructured Text markup notation.

Please read the Documentation/process/changes.rst file, as it contains the 
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.

***   

![GitHub last commit](https://img.shields.io/github/last-commit/SangwoonYun/Trapfetch_Kernel)
![GitHub contributors](https://img.shields.io/github/contributors/SangwoonYun/Trapfetch_Kernel)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/SangwoonYun/Trapfetch_Kernel)

***   

### Project Reference   
> [J. Won, O. Kwon, J. Ryu, J. Hur, I. Lee and K. Kang, "Trapfetch: A breakpoint-based prefetcher for both launch and run-time," 2017 IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2017, pp. 2766-2771, doi: 10.1109/SMC.2017.8123045.](https://ieeexplore.ieee.org/abstract/document/8123045 "Go IEEExplore")   

***   

### Build Package
```bash
sudo apt-get install -y build-essential libncurses-dev bison flex libssl-dev libelf-dev
```

***

### Linux Source Code (v5.10.8)
> Link: [Elixir.bootlin.com](https://elixir.bootlin.com/linux/v5.10.8/source "Go Linux Source Code")

***

### Files to be modified
> * include/linux/ptrace.h   
> * include/uapi/linux/ptrace.h   
> * kernel/entry/common.c   
