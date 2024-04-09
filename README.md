# TMC_BLDC_Hardware
TMC_BLDC 电路板部分

## TMC_BLDC
[TMC_BLDC 软件部分](https://github.com/Sandman6z/TMC_BLDC)

[TMC_BLDC HAL](https://github.com/Sandman6z/TMC_BLDC_HAL)

## BUGList:
- v1.1

| No. | BUG                                           | Check |
| :-: | --------------------------------------------- | :---: |
|  1  | add 12V, 5V, 3.3V test pad                    |       |
|  2  | remove HALL                                   |       |
|  3  | remove Q8                                     |       |
|  4  | remove R65                                    |   √   |
|  5  | Change PMOS package (Q1), Rgs (R27), Rg (R24), R14, R15 |       |
|  6  | Crystal & capacitor package                   |       |
|  7  | Inner Power layer shrinks 15mil               |       |
|  8  | LDO current change from SOT-223 to SOT-89     |       |
|  9  | Add a current sense resistor to one phase due to DC offset |       |
| 10  | Consider adding a power input fuse            |       |
| 11  | Replace reset circuit with CAT809 chip        |       |
| 12  | Add a resistor in series with an active crystal oscillator, and paralleling a large capacitor with a FB |       |
| 13  | Add an LED in a specific location if have space |       |
| 14  | Add Turbo Temp Port                           |       |