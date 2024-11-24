# SYSTEM DESIGN
This is where I take notes of my System Design Learning Journey.
I am following the [System Design Fundamentals](https://www.youtube.com/watch?v=lX4CrbXMsNQ&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf) by [ByteByteGo](https://www.youtube.com/@ByteByteGo)

# DAY 1:
## Computer Memory and Storage:
![image](https://github.com/user-attachments/assets/21930213-1834-4bb2-acd8-e57b72e2fefd)

**Memory**
First up, we have the fundamental duo: RAM and ROM.
RAM (Random Access Memory):
  Type of memory that stores data temporarily while the computer is running. It's fast and flexible, juggling all the programs we're running at any given time. However, RAM is volatile, meaning iut loses its stored data when the power is turned off.
Let's explore the different types of RAM, including SRAM, DRAM and everything in between:
- SRAM:
    Static Random Access Memory is a fast and expensive type of RAM used in high-speed applications like CPU caches, where quick access time is crucial.
- DRAM:
    Dynamic Random Access Memory is slower and cheaper than SRAM. It needs to be constantly refreshed to retain data, making it more high-maintenance. There are many types of DRAM with each generation bringing faster speeds and increased efficiency:
  - FPM DRAM
  - EDO DRAM
  - SDRAM
  - DDR SDRAM
Many are obsolete, and the common types of DRAM in the market today are DDR, variants like DDR4 and DDR5. GDDR6 is also worth mentioning as it is a specialized type of DRAm optimized for faster data transfer rate, which the GPU needs for its massive parallel processing. GDDR6 is the most widely used today.

ROM (Read Only Memory):
  Type of memory that retains data even when the power is off. It's non-volatile and used to store essential information, like firmware and the BIOS, that your computer needs to boot up. 
  - Firmware is a type of software stored in ROM that controls how hardware devices communicate with each other.
  - BIOS or Basic Input Output System, is the first software your computer runs when you power it up. It's responsible for starting the computer, initializing hardware components, and handing over the control to OS.

**Storage**
- Hard Disk Drive
  HDDs have been around for a long time. Introduced By IBM in 1956. They store data on spinning magnetic disks and are known for their large storage capacitites at a low price. 
- Soft State Drive
  SSDs use NAND-based flash memory, providing faster data access, reduced power consumption and increased durability compared to HDDs, but come at a higher price. NVMe, or Non-Volatile Memory Express, is a high-performance interface for SSDs that connects directly to the CPU via PCIe lanes. This aallows for lower latency and significantly faster data transfer rates compared to SATA-based SSDs.
Need to take your data on the go?
- Flash Drive
  Flash Drives also known as USB drives or thumb drives, are small, plug-and-play devices you can use with any USB port. They are easy to use and perfect fro transferring files between computers.
- SD cards
  SD cards are commonly found in phones and camera. They are smaller than a postage stamp but can stroe thousands of files. SD card comes in three main physical sizes: SD, microSD and miniSD.




