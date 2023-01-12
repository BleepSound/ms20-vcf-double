# Populate Manual for MS20-VCF

Follow this manual to populate the PCB: 

The basic rule is, always go from the smallest to the highest component on the board !

- [[front | ]] This is the front side of the board we are populating
- [[back | ]] This is the back side of the board we are populating, and we are gonna start by this side.
- [[back | U1 ]] Start by the SMD components, here U1. 
- [[back | FB2, FB1, R4 ]] After U1, do the beads and the resistor
- [[back | C9, C10, C5 ]] Do all the ceramic capacitors
- [[back | C6, C3, C2 ]] Finish the capacitors with the electrolytic ones, watch out for their orientation, they are polarized.
- [[back | D1, J5, ResLv1, ResVol1 ]] Finish the back by putting the trimmers, the power LED and the power connector. The LED shouldn't touch the backside of the PCB. 

The back is done, we can flip the PCB and start the front !

- [[front | ]]
- [[front | D2, D3, D4, D5, D6, D7 ]] First, populate all the diodes.
- [[front | R2, R6, R7, R11, R15, R16, R1, R3, R12, R13, R5, R9, R20, R8, R21, R22, R10, R19, R14, R17, R18 ]] You then can do all the resistors (by value so you don't make mistakes)
- [[front | Q1, Q2 ]] You then can add the transitors, watch out for their orientation.
- [[front | U2 ]] Add the socket for the TL072, making sure you get the orientation right. Don't add the Tl072 yet, you'll add it at the end. 
- [[front | C1, C4 , C7, C8]] Add the capacitors

The last step concern the jacks, potentiometers and switches. Basically, anything that is accessible throught the front panel. You first place them.

:warning: DO NOT SOLDER THEM YET :warning:

(this is really important !!)

- [[front | SW1, CUTCV1, CUTOFF1, Res1, J6, J7, J8]] Do Not Solder Them! place them first and put the front panel in place. *For the pot **CUTCV1**, use the small 100k pot (not D shaped)* The other pots are for CUTOFF1 and Res1. You'll be able to put the" knobs of your choice on those.

You then put in place the front panel, making sure everything fits. Once all the jack sockets and switches are fastenned to the front panel, you can solder them, and only then !!!

## Conclusion

This is the end of the build, if yoy have any questions, don't hesitate !