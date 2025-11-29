# Easy Retirement Calculator

Calculates and visualizes your years to retirement based on an income-agnostic your savings rate.

[Link](https://peticol.as/easy-retirement)

## Math

$t = \frac{\ln\left(\frac{m(1-S) \cdot r + S}{E \cdot r + S}\right)}{\ln(1 + r)}$

|     | description                                     | default |
|-----|-------------------------------------------------|---------|
| $t$ | years until target                              | `-`     |
| $S$ | savings rate                                    | `0.15`  |
| $r$ | annual rate of return                           | `0.05`  |
| $E$ | existing savings as multiple of annual spending | `0`     |
| $m$ | retirement multiplier                           | `25`    |