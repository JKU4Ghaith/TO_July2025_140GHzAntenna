# Coplanar140GHzAntenna

Design of coplanar 140GHz antenna with reflector on chip.  
Normally is the distance between TM2 and M1 very small for D-Band antennas, therefore they would not have high efficiency.  
whithin this design, we have moved the reflector outside off the chip to have at minumum about x20 distance between antenna and reflector.  
There is no schematics for the design.  
We have choosen coploanar to prevent feed line to be affected by changing the height of GND-reference.  
Simulations of patch and feedline with different stacks can be run from design_data/openEMS.  

The original stack from IHP was extended with non conductive adhesive material, to fill the gap under the chip in PCB.
Gap in PCB can be achieved with micro via or depth routing.
Original design for patch was done for 200 um spacing.
Results for patch are:  

| Reflector placement | Simulated Gain in dB |  
| :----        |    :----   |  
| M1 | -15 |  
| Sub+0um adhesive | 1 |  
| Sub+100um adhesive | 2.72 |  
| Sub+200um adhesive | -0.8 |  
| Sub+300um adhesive | -3.8 |  
| Sub+400um adhesive | -4.2 |  

GDS file to run simulations would be added later to do not confuse the submit system, but simulation results are there!.  
We see that the distancing has improved the antenna performance a lot!  
Additional calibration structures were added to layout to validate the design.  