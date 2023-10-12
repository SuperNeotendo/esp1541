

 Commodore 1541 Floppy drive Emulator (Scientist Study)
 
 this code is a try to emulate an 1541 floppy drive
 with an esp32 running @240Mhz.
 currently there is an 6502 emulation with 6522 registers debugging,
 it is running in full speed (not cycle accurate).
 maybe use 6502 emulation on Core-0 and 6522 Emulation on Core-1
 
 6502 Emulation
 2Kb RAM
 1541 ROM
 6522 Registers Debug, LED is using the built-in esp led
 
 1541 ROM code is running and is doing a lot
 i added an simulated IRQ at every 256 MOTOR OFF cycles for demonstrating 6502 IRQ


 
 feel free to use it for whatever you want
 just give credit to me instagram.com/SuperNeotendo
