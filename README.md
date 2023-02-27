![pip80 logo](assets/logo/pip80-logo-128.png)

# pip80 game console
The **pip80** is an open-source and collaborative Z80 based homebrew game console. This project was born from the idea that many existing z80 projects are built in an organic way. These projects start with simple goals but, over time, they almost always become increasingly complex.

The **pip80** is designed to be modular and aims to reduce the runaway effect of adding new components to a single board project. Each module is separated onto it's own board with the following goals:

 - Reduce single board complexity
 - Easier to isolate tests
 - Greater separation of interests

<br />

> **Warning**: **This project is just starting out and therefore not production ready.**

<br />

# 🔹Schematics

You can find schematics for the pip80 at [I'm an inline-style link](https://www.google.com).

<br />

# 🔹Project goals

The **pip80** project aims to provide a simple z80 computer project that balances simplistic design and high performance. Ideally, anyone should be able to build a **pip80** computer onto a breadboard, with minimal technical knowledge.

The **pip80** is based on a modular design that consists of the following modules:

- Timing
- I/O
- CPU and DMA
- Banked memory
- OPL2 audio
- VGA graphics

For increased performance, we have included a **DMA** chip into the **pip80** design. This allows us to deliver data to the sound and/or graphics modules at high speed whilst freeing the CPU for other operations.

<br />

# 🔹 Components


### ❇️ Timing module

Coming soon...

<br />

### ❇️ I/O module

Coming soon...

<br />

### ❇️ CPU and DMA module

- Z84C0020PEC (20MHz CPU)
- Z8410AB1 (4MHz DMA controller)

<br />

### ❇️ Banked memory module

Coming soon...

<br />

### ❇️ Audio module

- YM3812 (3.58MHz OPL2 audio chip)
- Y3014B (DAC for the YM3812)
- TL072CP (Dual Op Amp)
- SN74HC595N (Shift register)
- 1N4148 (Signal switching diode)
- 3.5mm Audio Connector (Headphone socket)

<br />

### ❇️ VGA graphics module

Coming soon...

<br />

# 🔹SDK

Coming soon...

<br />

# 🔹Memory map

Coming soon...

<br />

# 🔹Examples

Coming soon...

<br />

# 🔹Credits
* [Machine learning icons created by Flat Icons](https://www.flaticon.com/free-icons/machine-learning)
