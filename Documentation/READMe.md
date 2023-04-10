# About this printer

The CZ-300 is sold by a company called Crazy3DPrint, which seems to be a branch of XYZPrinting. Seeing as a lot of the parts for the CZ-300 are loaned from XYZPrinting's Davinci Series, this makes sense. Therefore, forums and files for some DaVinci models applies for this printer as well. After close inspection, it seems like Crazy3DPrint planned on selling "add-on" modules for this printer. I say this because fitting a second linear rod for example, needs a custom piece of plastic which was never included. The same goes for the hotend, as there seems to be additional "slots" for mounting an ABL-sensor or part cooling-fan. I could not confirm or find any additional modules myself. 

## Parts list 
### Frame: 
The frame is almost entirely made out of 2020 V-slot aluminum extrusions. A noteworthy discovery about these extrusions are the 4 holes inside the extrusions. These holes are almost certainly a cost cutting measure, and results in potentially higher vibrations and resonance. The Y-Axis and X-Axis movements uses linear rods, and some sort of spacer as a linear bearing. Although this spacer has great tolerances, it will wear with time. The Z-Axis is driven by unusual V-roller wheels, and the entire vertical assembly is pretty unstable. The 5mm Z lead screw is thin in comparason to other printers, and the addditional force because of the belt-driven dual Z leads to bending over time. Components like the motor mounts seem to be custom made. The feet are generic rubber feet which match the dimensions of those in the Tevo Tornado. Other components include 90 degree aluminum brackets, steel mounting plates and 4mm nuts and screws. For more details, see pictures or the modeled printer. 

**I had a very unpleasant experiance with the screws on this printer. I have, to date, had about 4 4mm screws snap on me. Please be careful disassembling and reassembling this printer, and _do not overtighten the screws!_**

### Hotend:
The hotend assembly seems to originate from XYZPrinting's Da Vinci Mini (+ Maker and 1.0 Pro) models. The threading nor any other specs are known about this hotend. It is **most likely** a 24V hotend, and seems to use a generic 100K thermistor. The 4010 24V hotend-cooling fan also acts as a part cooling fan, but barely does anything for part-cooling. The high noise threshold is not because of the fan, but rather because of the motherboard. I know this because it makes much less noise running of an SKR Mini E3 V2. 

### Bed: 
The bed carrier plate is extremely heavy. Like the X-axis, it uses a plastic mount with spacers as linear guides. Additionally, there is only a single linear rod - which causes to a lot of problems. What should have been the other linear rod is instead occupied by a 2020 v-slot extrusion and a steel "guide" which seems to support some of the bed's weight. Underneath and above the guide is a PTFE-like gliding-material, much like those used in computer-mice to minimize friction. This poor movement mechanism causes a lot of play and wear. The Y-Axis belt has a tendency to skip, especiallty when printing at faster speeds. I believe that this is because of the tremendous weight of the Y-Axis carrying plate. The weight can be reduced by either creating a custom aluminum plate and/or by replacing the glass bed for a spring steel one. 

## Credit: 
Thanks to Reddit user u/Jannoke (Also a contributer now!) for sharing a substancial amount of information on this printer. Also contributed to the CAD recreation. 
