Standig 899D Combo Hot Air & Soldering Station

Here is a mostly complete schematic and PCB pics of my 899D combo hot air & soldering station. 
Note, the schematic is a modified copy of the schematic from acbaruth/898D repository.  I have
not checked every component to see it they are correct for the 899D however the PCBs are 
simmular but not identical.

The Standig unit uses a 6 pin soldering iron connector. I have also used a Yihua 907H soldering
iron sucessfully (as it comes with a 6pin plug and has a movement sensor).  But the interal 
connections of the iron must be modified by swapping over two wires as per the 899D schematic
for it to work.  

The Standig uses front panel switches (SMD Rework Station and Soldering Station) to switch
230V AC to the unit.  However these switches also have 5V logic for the soft switching
with I suspect with no internal protection! Simmulary the PCB has poor track layout and 
seperation between the 230V and the 5V parts with no PCB cutouts providing tracking distance 
enhancement.  

Also note:  Bleed resistor R4, in the Top Header area of the schematic, which is the 230V AC
control to the Hot Air heater needs to be changed to 560K 1/2W as a min, it is supplied with
120K 1/8W and mine was black due to overheating. I have also fitted a heatsink to the hot air
fan motor controller triac as mine was hot after a short period of use.  
