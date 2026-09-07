# Conventions and Units of Measurement (MC-02-03 §6)

## Small Caps (§6.1)
The following are set in small caps in Microchip documentation:
AVDD, AVSS, CEXT, CIN, COUT, CREF+, CREF-, CVREF, FCLK, FOSC, ICC, IDD, ILI, ILO, IU, RDS(ON), REXT,
TA, TAA, TAD, TBUF, TCY, TF, THIGH, TIRVST, TLOW, TOF, TR, TSP, TWC, VAIN, VBAT, VBUS, VCELL, VDC,
VDD, VHYS, VIH, VIL, VOC, VOL, VPP, VREF, VREF+, VREF-, VSS, ZAIN

## SI Units (§6.2)
| Symbol | Unit |
|---|---|
| A | ampere |
| f | farad |
| Hz | hertz |
| h | hour |
| m | meter |
| Ω | ohm |
| Pa | pascal |
| s | second |
| V | volt |
| W | watt |

## Unit Prefix Symbols (§6.3)
| Symbol | Prefix | Power of Ten | Power of Two |
|---|---|---|---|
| c | centi | 10⁻² | – |
| G | Giga | 10⁹ | 2³⁰ |
| k | kilo | 10³ | – |
| m | milli | 10⁻³ | – |
| M | Mega | 10⁶ | 2²⁰ |
| n | nano | 10⁻⁹ | – |
| p | pico | 10⁻¹² | – |
| T | Tera | 10¹² | 2⁴⁰ |
| μ | micro | 10⁻⁶ | – |
| K (binary) | Kilo | – | 2¹⁰ |

- Lowercase "u" is only a substitute for the Greek "μ" (micro) symbol when μ is unavailable (e.g.,
  plain ASCII text). Use the real μ symbol in Office/Adobe documents and anywhere it's supported.
- Uppercase "K" = ×1024 (2¹⁰), used only for memory size. Lowercase "k" = ×1000 (10³) for everything else.

## Common Unit Symbols (§6.4)
Always use the **preferred representation** — convert any "other representation" you see.

| Preferred | Meaning | Convert these to preferred |
|---|---|---|
| b | bit | Bit |
| B | byte | Byte |
| Kb | kilobit | Kbit |
| KB | kilobyte | Kbyte, K byte |
| Kword | kilo-computer/machine word | K word |
| Mb | Megabit | Mbit |
| MB | Megabyte | MByte |
| MIPS | Million Instructions Per Second | mips |
| rad | Absorbed dose of radiation | RAD |
| bps | bits per second | bits/s |
| Bps | Bytes per second | B/s |
| Gbps | Gigabits per second | Gbit/s, Gb/s |
| GBps | Gigabytes per second | GB/s |
| kbps | kilobits per second | kbit/s, kb/s |
| kBps | kilobytes per second | kB/s |
| Mbps | Megabits per second | Mbit/s, Mb/s |
| MBps | Megabytes per second | MB/s |
| Tbps | Terabits per second | Tbit/s, Tb/s |
| TBps | Terabytes per second | TB/s |
| kbaud | kilobaud | kBd, k baud |
| Hz / kHz / MHz | hertz / kilohertz / megahertz | KHZ, khz, MHZ (all wrong) |
| kΩ | kilo-ohm | kOhm |
| sps | samples per second | SPS |
| ksps | kilosamples per second | KSPS |
| Msps | megasamples per second | MSPS |
| bpp | bits per pixel | BPP |
| bps | bits per sample | BPS |
| Krad / Mrad / mrad | kilorad / Megarad / millirad | — |

## Names of Bits, Modes, Pins and Other Terms (§6.5)
Many terms in technical documentation share names (e.g., a "Doze" mode and a "DOZE" bit). Always
follow the identifier's exact casing to disambiguate:

| Identifier | Formatting rule |
|---|---|
| Bit | Register bit name: ALL CAPS. Generic bit description: Initial caps (e.g., "Stop bit," "Start bit," "Status bit") |
| Command | Generic commands: lowercase |
| Condition | Initial caps (Reset/Stop/Start), unless it's an acronym (e.g., ACK) |
| Event | Lowercase, except "Special Event Trigger" |
| Flag | Initial caps |
| Interrupt | Lowercase |
| Mode | Initial caps (but not the word "mode" itself) |
| Module | Lowercase (including the word "module"), unless the name is itself an acronym |
| Register | Bold |
| Signal | Initial caps (e.g., "Reset") |
| State | Initial caps |

Example: "Doze mode" (Mode identifier, initial cap, "mode" lowercase) vs. "DOZE bit" (register bit
name, ALL CAPS).
