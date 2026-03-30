This applies only to the 64-pin QFP variant.

It is not confirmed if the programming mode even exists on the non-P 78K/2. Use at your own risk.

| Pin | Our normal function | PROM normal function | Programming function |
|-----|-----------------|----------------------|--|
| 1   | ~RD | ~RD | ~OE |
| 2   | A19 | A19 | pull low w/ 10k |
| 3   | A18 | A18 | pull low w/ 10k |
| 4   | A17 | A17 | pull low w/ 10k |
| 5   | A16 | A16 | pull low w/ 10k |
| 6   | ~RESET | ~RESET | ~RESET |
| 7   | X2 | X2 | Short low |
| 8   | X1 | X1 | Leave floating |
| 9   | Vss | Vss | Vss |
| 10  | A15 | A15 | A15 |
| 11  | A14 | A14 | A14 |
| 12  | A13 | A13 | A13 |
| 13  | A12 | A12 | A12 |
| 14  | A11 | A11 | A11 |
| 15  | A10 | A10 | A10 |
| 16  | A9  | A9 | pull low w/ 10k |
| 17  | A8  | A8 | A8 |
| 18  | AD7  | AD7 | D7 |
| 19  | AD6  | AD6 | D6 |
| 20  | AD5  | AD5 | D5 |
| 21  | AD4  | AD4 | D4 |
| 22  | AD3  | AD3 | D3 |
| 23  | AD2  | AD2 | D2 |
| 24  | Vss | Vss | Vss |
| 25  | AD1  | AD1 | D1 |
| 26  | AD0  | AD0 | D0 |
| 27  | ASTB | ASTB | Leave floating |
| 28  | NMI | NMI | NMI (apply +12?) |
| 29  | int. P0 | int. P0 | A9 |
| 30  | int. P1 | int. P1 | Short low |
| 31  | int. P2 | int. P2 | Short low |
| 32  | int. P3 | int. P3 | Short low |
| 33  | int. P4 | int. P4 |  Short low |
| 34  | int. P5 | int. P5 | Short low |
| 35  | SI | SI | Short low |
| 36  | RX D | RX D | Leave floating |
| 37  | TX D | TX D | Leave floating |
| 38  | ~SCK | ~SCK | pull low w/ 10k |
| 39  | SB0 | SB0 | pull low w/ 10k |
| 40  | ~EA | ~EA | Apply Vpp |
| 41  | Vdd | Vdd | Vdd |
| 42  | AVss | AVss | pull low w/ 10k |
| 43  | AVref | AVref | pull low w/ 10k |
| 44  | AN5 | AN5 | pull low w/ 10k |
| 45  | AN4 | AN4 | pull low w/ 10k |
| 46  | AN3 | AN3 | pull low w/ 10k |
| 47  | AN2 | AN2 | pull low w/ 10k |
| 48  | AN1 | AN1 | pull low w/ 10k |
| 49  | AN0 | AN0 | pull low w/ 10k |
| 50  | TO0 | TO0 | Leave floating |
| 51  | TO1 | TO1 | Leave floating |
| 52  | TO2 | TO2 | Leave floating |
| 53  | TO3 | TO3 | Leave floating |
| 54  | P00  | P00 | A0 |
| 55  | P01  | P01 | A1 |
| 56  | P02  | P02 | A2 |
| 57  | P03  | P03 | A3 |
| 58  | P04  | P04 | A4 |
| 59  | P05  | P05 | A5 |
| 60  | P06  | P06 | A6 |
| 61  | P07  | P07 | A7 |
| 62  | AN7  | AN7 | pull low w/ 10k |
| 63  | AN6  | AN6 | pull low w/ 10k |
| 64  | ~WR  | ~WR | ~CE |

Main points: 
 - A9 changes pins entirely
 - A/D pins become strictly A pins, D pins appear on other side of package
