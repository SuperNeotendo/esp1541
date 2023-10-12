# esp1541
Commodore 1541 Floppy drive Emulator (Scientist Study)

this code is a try to emulate an 1541 floppy drive with an esp32 running @240Mhz. currently there is an 6502 emulation with 6522 registers debugging, it is running in full speed (not cycle accurate). maybe use 6502 emulation on Core-0 and 6522 Emulation on Core-1

- 6502 Emulation
- 2Kb RAM
- 1541 ROM
- 6522 Registers Debug
- LED is using the built-in esp led (ESP32-WROOM32)

1541 ROM code is running and is doing a lot i added an simulated IRQ at every 256 MOTOR OFF cycles for demonstrating 6502 IRQ

feel free to use it for whatever you want just give credit to me https://instagram.com/SuperNeotendo
<img width="560" alt="Screenshot 2023-10-13 004910" src="https://github.com/SuperNeotendo/esp1541/assets/45854100/cb08bcac-0340-4b77-9193-b489feacef0a">
<img width="533" alt="Screenshot 2023-10-13 004938" src="https://github.com/SuperNeotendo/esp1541/assets/45854100/ff55f241-5d9f-4dd9-919b-d6269868230a">
