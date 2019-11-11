# TuobaOS
A Customized distribution for Embedded, IoT/Edge, Cloud/DataCenter, and so on. 

Developer friendly Linux distribution images that target at on Open Hardware development boards to achieve the following goals gradually:

Stage 1 
   1.1 base on an existed distribution like Fedora, Manjaro, and so on 
   1.2 upstreaming Linux Kernel with all the necessary HCI related features (e.g., eBPF, Virtualization, Debugging, Networking,     
        Storage…)enabled according to our design 
   1.3 all the necessary development required packages (such as that for programming language runtimes, developer toolkits, 
        virtualization softwares, devops utilities, HPC/AI frameworks, security tools, and so on) are preinstalled.
   ...

Stage 2
   Get rid of the old GNU softwares and corresponding dependencies as much as possible, such like: 
   2.1 remove GCC and use LLVM as the default toolchain to build everything like Linux Kernel
   2.2 replace glibc with musl libc (http://www.musl-libc.org/) upstreaming Linux Kernel with our own customization, 
       especially for eBPF related code, and an In-Kernel messaging bus
   ...
  
Stage 3
   3.1 replace musl libc with llvm-libc (https://llvm.org/docs/Proposals/LLVMLibC.html) if the later is mature enough 
   3.2 upstreaming Linux Kernel with all the In-Kernel services work as expected according to our design  
   ...


    

