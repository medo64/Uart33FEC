### Uart33FEC

#### Parts

|  # | Part                                              | RefDes  | Preferred Part Number       |
|---:|---------------------------------------------------|---------|-----------------------------|
|  2 | C 47pF NP0 16V (0805)                             | C1-C2   | 399-C0805C470J5GAC7800CT-ND |
|  1 | C 10nF X7R 16V (0805)                             | C3      | 399-17617-1-ND              |
|  3 | C 100nF X7R 16V (0805)                            | C4-C6   | 478-5311-1-ND               |
|  5 | C 10uF X5R 16V (0805)                             | C7-C11  | 1276-1096-1-ND              |
|  1 | D Schottky 30V 800mA [CUS08F30,H3F] (SOD323)      | D1      | CUS08F30H3FCT-ND            |
|  1 | D TVS 3.3V D1213A-02SOL-7 (SOT23-3)               | D2      | D1213A-02SOL-7DICT-ND       |
|  2 | DS LED (0805)                                     | DS1-DS2 | 475-1415-1-ND               |
|  1 | J USB C, plug, straddle 0.8mm                     | J1      | WM12855-ND                  |
|  1 | J JST XH Vertical (4w)                            | J2      | 455-B4B-XH-A-ND             |
|  1 | L Ferrite 600R@100Mhz                             | L1      | 240-2390-1-ND               |
|  2 | R 27 1% (0805)                                    | R1-R2   | 738-RMCF0805FT27R0CT-ND     |
|  2 | R 1K 0.125W (0805)                                | R3-R4   | RMCF0805FT1K00CT-ND         |
|  1 | R 5.1K 0.125W (0805)                              | R5      | RMCF0805FT5K10CT-ND         |
|  1 | R 10K 0.125W (0805)                               | R6      | RMCF0805FT10K0CT-ND         |
|  1 | R 75K 0.125W (0805)                               | R7      | RMCF0805FT75K0CT-ND         |
|  1 | U Transciever Uart FT230XS (SSOP-16)              | U1      | 768-1154-5-ND               |
|  1 | U LoadSwitch Adjustable [AP22652W6-7] (SOT23-6)   | U2      | 31-AP22652W6-7CT-ND         |
|  1 | VR Linear 3.3V 1000mA AZ1117IH-3.3TRG1 (SOT223)   | VR1     | AZ1117IH-3.3TRG1DICT-ND     |
|  2 | H Screw M2x3mm                                    | -       | -                           |


#### Specifications

| Property        | Value                          |
|-----------------|--------------------------------|
| PCB size        | 24.0 x 27.9 x 0.8 mm (1.1 in²) |
| Voltage (in)    | 5 V ±10%                       |
| Current (in)    | 450 mA (max)                   |
| Voltage (out)   | 5 V ±15%                       |
| Current (limit) | 400 mA ±10%                    |


#### FTDI Configuration

| Setting | Value  |
|---------|--------|
| CBUS0   | TXDEN  |
| CBUS1   | TXLED# |
| CBUS2   | RXLED# |
| CBUS3   | PWREN# |
