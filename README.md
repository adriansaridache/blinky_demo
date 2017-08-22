#blinky_freertos_demo

1. install gcc-arm-none-eabi-6-2017-q2-update-win32-sha2.exe
2. inside (project)/components/toolchain/gcc make sure the Makefile.posix and Makefile.windows have GNU_INSTALL_ROOT set to where GNU Tools ARM Embedded/6 2017-q2-update is installed
3. Add the following argument to System Environment Variables C:\Program Files (x86)\GNU Tools ARM Embedded\6 2017-q2-update\bin