# 2.4 GHz Wi-Fi Antenna Feed Matching

Academic project for ECE 3300 Electromagnetics I.

## Goal
Design a quarter-wave transformer to match a 100 Ω antenna feed to a 50 Ω RF source at 2.4 GHz.

## Design
The transformer was designed for a RO4350B substrate and simulated in Ansys HFSS. The project examined input impedance, S11, bandwidth, and the effect of changing the transformer geometry.
## Simulation results

At 2.4 GHz, the HFSS report showed the following input reflection
(S11) as the middle-strip width changed:

| Middle-strip width | Reported S11 |
| --- | ---: |
| 1.00 mm | −5.39 dB |
| 1.92973 mm (calculated design) | −9.95 dB |
| 3.53 mm | −39.15 dB |

The plotted terminal S-parameters used 50 Ω reference impedances
at both ports, although the second lumped port was configured as
100 Ω. The 3.53 mm result therefore needs to be checked with a
100 Ω reference at the second terminal before it can be interpreted
as a verified 50 Ω-to-100 Ω match.

## Project report

[Read my ECE 3300 project report](Janowiecki_ECE330_project.pdf)

**Report correction:** The guided wavelength should read 0.0771 m
(77.1 mm), not 0.771 m. The quarter-wave length of 19.275 mm is correct.
