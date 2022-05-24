# US18650VTC6_OCV_SOC_Curve
Open-circuit voltage over state of charge curve for Sony/Murata US18650VTC6 Li-ion cell.

Measurement setup:
1) Cell is charged to 4.2 V
2) Cell is rested for 24 h
3) Cell is discharged with C/20 (~ 150 mA) until terminal voltage hits 2.5 V
4) While discharging, voltage and discharged energy are logged
5) Cell is rested for 24 h
6) Charge cell with C/20 until terminal voltage hits 4.2 V
7) See 4)
8) Average of both curves represents roughly OCV(SOC) curve

This curve is used to estimate the state of charge of a battery pack. This method is only valid after a resting period to ensure that the terminal voltage equals the open-circuit voltage. May be used to support coulomb counting.
