> 🇹🇷 [Türkçe versiyon için tıklayın (Turkish Version)](README-tr.md)
# 8-Bit Custom Computer (English)

This project is a permanent, modular PCB hardware revision of the legendary [8-bit breadboard computer architecture by Ben Eater](https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU). While the original project was built on breadboards, this repository contains the professional PCB layouts, stabilized power/signal routings, and manufacturing files.

## Modules
### 1. Clock Module (`/Clock-Module`)
The heart of the system.
* **Features:** Adjustable clock frequency, manual single-stepping, and Halt signal support.
* **Design:** Built with NE555 timers and 74LS series logic gates. The routing is optimized for single-layer DIY manufacturing with proper decoupling topology for signal integrity.
> [!NOTE]
> **Project Status / Work in Progress:** The PCB designs for the remaining modules (ALU, Registers, RAM, etc.) have not been completed yet. The bus architecture and PCB connector pinouts are not finalized and are subject to change in future revisions as the system expands.
