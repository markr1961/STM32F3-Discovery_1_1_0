A copy of ST's F3-Discovery demonstration and example code circa 2012

Note: IRQ function names are different from newer version of CMSIS. 
This was intentionally not changed to maintain compatibility with demo code.
If this code is ported to a newer HAL or CMSIS, it will probably break the compile.

the startup_stm32f30x.s was modified to build with newer versions of IAR.
 "SECTION .text:CODE:REORDER" changed to "SECTION .text:CODE:NOROOT:REORDER"

modified code to run a 1mS sytick instead of 10mS.
