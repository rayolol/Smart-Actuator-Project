# Smart-Actuator-Project
this is a smart actuator ecosystem I'm trying to build. like Legos, modular submodule, easy to design.

this in devlopment


this project currently contains

- a cycloidal assembly
- a planetary assembly
- a PCB design (not tested) of the smart actuator

the PCB is an FOC controller build with the TMC6200 and the stm32g491 mcu. 
- it has CAN bus support,
- SPI encoder support,
- i2c encoder support,
- uart open port for debugging.
- a usb port,
- integrated phase current sensing,
- a bus current and voltage sensing,
- reverse polarity protecttion temperature sensing on each mosfet.
- and an FPC cable for extra protocols and pins of additionnal sensors and peripherals.
- configurable dump volatge threshold of back emf volage spikes 

the target specs for this board is 30 amps at an operating range of 12-24v and the current dimetions are sitting at 45mm diameter.

the mechanical part of this project contains a 16:1 planetary gearbox and a 15:1 cycloidal gearbox.
the target is to make them interchangable with the housing and having a universal pinout and socket. for the prototype is not done yet. 
they are currently being printed in resin for POC and protoryping purposes

