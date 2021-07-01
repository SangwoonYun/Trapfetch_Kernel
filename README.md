# Trapfetch

![GitHub last commit](https://img.shields.io/github/last-commit/SangwoonYun/Trapfetch_Kernel)
![GitHub contributors](https://img.shields.io/github/contributors/SangwoonYun/Trapfetch_Kernel)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/SangwoonYun/Trapfetch_Kernel)



### Project Reference   
> [J. Won, O. Kwon, J. Ryu, J. Hur, I. Lee and K. Kang, "Trapfetch: A breakpoint-based prefetcher for both launch and run-time," 2017 IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2017, pp. 2766-2771, doi: 10.1109/SMC.2017.8123045.](https://ieeexplore.ieee.org/abstract/document/8123045 "Go IEEExplore")   


### Build Package
```bash
sudo apt-get install -y build-essential libncurses-dev bison flex libssl-dev libelf-dev
```


### Linux Source Code (v5.10.8)
> Link: [Elixir.bootlin.com](https://elixir.bootlin.com/linux/v5.10.8/source "Go Linux Source Code")


### Files to be modified
> * include/linux/ptrace.h   
> * include/uapi/linux/ptrace.h   
> * kernel/entry/common.c   
