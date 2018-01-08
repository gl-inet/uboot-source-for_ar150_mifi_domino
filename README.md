This is the uboot for GL-AR150 GL-MiFi and GL-Domino based on QCA9331 chipset. 

This uboot is based on pepe2k's uboot source code. 

Note: 
-------
This source code is published according to GPL License. 

You should bear the risk of compiling and Changing uboot yourself. We are not obliged to provide technical support related to uboot.


How to compile
-------------

modify Makefile, and change to your mips-openwrt real toolchain path
```
export TOOLPATH=...
```
then `make domino`

the uboot file will be in `bin` folder 
