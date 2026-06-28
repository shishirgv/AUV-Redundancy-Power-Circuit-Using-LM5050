LM5050 Dual Input Redundancy Circuit:-

Provide seamless power redundancy between
main battery and backup battery.

Each battery feeds the output through an
LM5050-controlled MOSFET acting as an ideal diode.

MOSFET Selection:-

Part: SUM40N10-30

Reasons:-
- Low RDS(on)
- Suitable VGS(th)[The selected MOSFET has a low gate threshold voltage (typically 1–4 V), allowing reliable enhancement by the LM5050 gate drive circuitry while maintaining a low RDS(on)]
- High current capability
- Used in TI reference design

PCB Design Points:-
- 1 mm power traces
- Ground pour on bottom layer
- ERC and DRC clean

Improvements:- 
- A zener diode can be added for more safety
- The routing should follow the 90 degree rule
- Pin mapping of used mosfet should be verified before confirming schematic
