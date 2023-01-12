# Populate Manual for MS20-VCF-Double-circuitboard

Follow this manual to populate the PCB: 

The basic rule is, always go from the smallest to the highest component on the board !

- [[front | ]] This is the front side of the board we are populating
- [[back | ]] This is the back side of the board we are populating, and we are gonna start by this side.
- [[back | U1, U3 ]] Start by the SMD components, here U1 and U3, the LM13700s. 
- [[back | FB2, FB1]] After the smd components, do the beads.
- [[back | C7, C8, C11, C12 ]] Do all the ceramic capacitors
- [[back | C1, C5, C10, C15 ]] Finish the capacitors with the electrolytic ones, watch out for their orientation, they are polarized.
- [[back | J8, ResLv1, ResVol1, ResLv2, ResVol2 ]] Finish the back by putting the trimmers and the power connector.

The back is done, we can flip the PCB and start the front !

- [[front | ]]
- [[front | D1, D2, D3, D4, D5, D6, D8, D9, D10, D11, D12, D13 ]] First, populate all the diodes.
- [[front | R1, R2, R5, R6, R17, R23, R24, R27, R28, R39, R3, R4, R10, R11, R25, R26, R32, R33, R13, R14, R18, R35, R36, R40, R7, R9, R29, R31, R15, R37 ]] You then can do all the resistors (by value so you don't make mistakes)
- [[front | Q1, Q2, Q3, Q4 ]] You then can add the transitors, watch out for their orientation.
- [[front | U2, U4 ]] Add the socket for the TL072, making sure you get the orientation right. Don't add the Tl072 yet, you'll add it at the end. 
- [[front | C2, C3, C4, C16, C17, C18, C6, C9, C13, C14]] Add the capacitors

## Conclusion

This is the end of the build, if yoy have any questions, don't hesitate !