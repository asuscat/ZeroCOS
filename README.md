# ZeroCOS
A entirely vibe coded OS written in C11

READ BEFORE USE!!!: THIS IS A ALPHA GRADE PRODUCT, NOWHERE NEAR FINISHED, IT WORKS ON QEMU, BUT REMAINS UNTESTED AS OF RIGHT NOW

Credit to chatbots used to create: claude, gemini, chatgpt

LISCENCING: none, because i dont know what liscening is so im publishing this at no liscencing information

READ BEFORE CREATING ISSUES: most issues will probably go unawnserd so dont get your hopes up, nontheless feel free to create pull requests or issues

WANT TO BUILD???:

download this file https://www.microchip.com/en-us/tools-resources/develop/microchip-studio/gcc-compilers
then download the riscv toolchain from your local repo
extract the avr toolchain then run 
chmod -R +x ~/avr8-gnu-toolchain-linux_x86_64/

start off by extracting the .zip and cding into the directory, THEN RUN make clean, then read the Makefile for more information on TIERS and running Make tier!

WANT TO RUN ON QEMU?:

compile with make run TIER=3
