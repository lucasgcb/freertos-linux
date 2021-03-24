# freertos-linux

Para compilar,

Siga as instruções em
https://www.freertos.org/FreeRTOS-simulator-for-Linux.html

```
Pre-requisites (the output below shows the versions used during testing):
gcc

$ gcc --version
gcc (GCC) 9.2.0
make

$ make --version
GNU Make 3.81
Copyright (C) 2006  Free Software Foundation, Inc.
libpcap (for networking support)

$ version: libpcap-devel-1.5.3-11.x86_64 
To install on ubuntu run
$ sudo apt-get install libpcap-dev
To install on rpm based system run
$ sudo yum install libpcap-devel
or
$ sudo dnf install libpcap-devel
To install on MacOS run
$ brew install libpcap
Alternatively, it is possible to install from source follow the instructions at INSTALL.md
Building the source code:
Navigate to the Demo Directory at: Demo source

 $ cd FreeRTOS/Demo/Posix_GCC/
To build run:
$ make
To clean run:
$ make clean
Running the Demo (check the instructions above on how to choose between the available demos)

Navigate to the newly created "build" directory
$ cd build 
Run the demo (blinky and full)

$ ./posix_demo
```
