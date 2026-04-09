# switch-lite-raspberrypi-mod
Hardware mod of a Nintendo Switch Lite using a Raspberry Pi microcontroller!
# Overview :D
I wanted to challenge myself by turning something i already own into something more versitale and special, so I integrated a Raspberry Pi into a Nintendo Switch Lite to create a custom handheld embedded system!
This project let me explore how hardware and softwarte come together in real-world systems, especially when yorue working with tight space, power limits and heat... (im a broke university student, i got my soldering iron from aliexpress and i did this all over my kitchen stove with 0 experience on how to solder...)

# Objectives
- Build a fully functional embedded system inside a handheld console
- Install an OS system
- Learn more about hardware + software integration
- Work within real physical constraints (space, power, thermals)
- Create something unique, fun

# System Architecture
**Core Components**
- Raspberry Pi Pico (RP2040)
- Nintendo Switch Lite (used as the enclosure + base hardware)
- Input/Output interface (USB C ribbon cable)

# Hardware Implementation
- Disasemble the Nintendo Switch Lite
- Fitted the raspberry pi inside with limited internal space and no microscope...
- Wired up power and connections by hand
- Made lots of small adjustments to get everything to fit in

# Thermal Challenges
When this project started i wasnt aware how important heat disipation was, so when i applied my thermal paste, i applied it ontop of the cover of the GPU instead of ontop of it physically. Everything being packed into such a small space meant heat built up super quick.
- identified overheating during testing
- Added thermal paste to improve cooling
- Rearranged components to help with airflow

# Software Implementation
- LineageOS: Turns the device into a mini android system, allows use of apps, customisation and a more modern interface
- Lakka: Retro gaming focused OS, provides a clean emulator environment
Multi-Boot Setup
- Configured the system to support multiple OS enviroments
- Set up boot selection and storage handling
- Ensured compatibility between different systems
 # Challenges
 If i havent wrote this already this is my first time ever soldering and i decided to experiment on a $300 device because why not... 

 - Lack of resources
 I also did this within my first year student flat so obviously no overhead extractor, i found myself moving between the kitchen stove for the fan and my windowsill.
 I also had to do this all without a magnifier. For reference, the whole devices dimensions are 208mm x 91 mm * 14mm, so i was performing wiring and hardware integration within a compact enclosure.

- Power instability
The system would randomly shut down or behave unpredictably at first. There were two main issues, i hadnt soldered a ribbon cable correctly and the voltage wasnt stable. It was all fixed after some thorough going over.

- Space constraints
Everything had to fit within a super small enclosure (two big ribbon cables, the raspberry pico pcb + usb c ribbon cable adapter). It took me having to cut up the cover of my GPU for the pcb to fit, and i reworked the layout multiple times until it all fit neatly!

# Future Improvements
- Improve battery life
- Make internal layout cleaner
- Improve cooling further
- Possibly design a custom pcb
- Getting better equipment

# Skills i gained!
- Embedded systems dev
- hardware prototyping
- power management

# Disclaimer
This project was done for learning and experimentation using my own device 💕

















