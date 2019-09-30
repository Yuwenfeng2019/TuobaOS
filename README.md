# TuobaOS
A Customized Distribution for Embedded, IoT/Edge, Cloud/DataCenter, and so on. 

This is a developer friendly distribution that target at on Open Hardware Platforms to achieve the following goals gradually:
1) Get rid of the old GNU softwares and corresponding dependencies as much as possible, such like: 
   1.1) remove GCC and use LLVM as the default toolchain to build everything.
   1.2) replace glibc with musl libc.
   ...
2) Upstreaming Kernel with customization.
3) Most of the development required packages (such as that for the runtime of popular programming languages, developer toolkits, 
   virtualization, devops utilities, AI frameworks, security tools, and so on) are preinstalled.

It will be implementented in two stages:
1) in the first or current stage, the images that we provide will base on an existed distribution like Fedora, Debian, and so on; 
2) in the second stage, we will fully customize a new distribution according to our design goals (will be explained in details later) 
   and setup our own package repositories if necessary.

    

