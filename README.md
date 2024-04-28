[UART 3.3V Framework Expansion Card](https://medo64.com/uart33fec/)
===================================================================

This Framework laptop expansion card will show up on your system as a serial
device and allow for a non-isolated serial UART communication up to 1 Mbaud
baud rate.

Please note that this card is not using RS-232 but 3.3V TTL.


## UART Pinout

To connect to this board, one has to use a 4-pin JST XH connector. The following
table represents the pinout, pin 1 being on the left as looking into the
expansion card.

| # | Ref | Description                     |
|--:|:---:|---------------------------------|
| 1 | RXD | Receive (3.3V TTL)              |
| 2 | GND | Ground connection               |
| 3 | TXD | Transmit (3.3V TTL)             |
| 4 | 3V3 | 3.3V 500mA output               |

Using 22 AWG wire 0.25 mm² is recommended.


## Supported Speeds

This board employs the FT232R as its UART chip, and consequently, it supports
all the baud rates this chip [can handle](https://ftdichip.com/Documents/AppNotes/AN232B-05_BaudRates.pdf).
The table below lists the standard baud rates.

| Baud rate |    Actual | Error |    Divisor |
|----------:|----------:|------:|-----------:|
|       300 |       300 | 0.00% |  10000.000 |
|       600 |       600 | 0.00% |   5000.000 |
|     1,200 |     1,200 | 0.00% |   2500.000 |
|     1,800 |     1,800 | 0.00% |   1666.625 |
|     2,400 |     2,400 | 0.00% |   1250.000 |
|     4,800 |     4,800 | 0.00% |    625.000 |
|     7,200 |     7,201 | 0.01% |    416.625 |
|     9,600 |     9,600 | 0.00% |    312.500 |
|    14,400 |    14,406 | 0.04% |    208.250 |
|    19,200 |    19,200 | 0.00% |    156.250 |
|    28,800 |    28,812 | 0.04% |    104.125 |
|    38,400 |    38,400 | 0.00% |     78.125 |
|    57,600 |    57,692 | 0.16% |     52.000 |
|   115,200 |   115,385 | 0.16% |     26.000 |
|   230,400 |   230,769 | 0.16% |     13.000 |
|   460,800 |   461,538 | 0.16% |      6.500 |
|   921,600 |   923,077 | 0.16% |      3.250 |
| 1,000,000 | 1,000,000 | 0.00% |      3.000 |

While chip does support baud rates up to 3 Mbaud, granularity of such rates
is severely limited.


---
*You can check my blog and other projects at [www.medo64.com](https://www.medo64.com/electronics/).*
