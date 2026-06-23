# Microwave-Bandpass-filter
This repository contains the design files, layout, and performance parameters for a high-frequency microwave passband filter.

## Specifications

The filter is designed to meet the following frequency and attenuation requirements:

| Band | Frequency Range | Parameter | Requirement |
| :--- | :--- | :--- | :--- |
| **Passband** | 3.23 GHz – 4.37 GHz | Return Loss (RL) | > 20 dB |
| **Lower Stopband** | 2.318 GHz – 2.592 GHz | Insertion Loss (IL) | > 55 dB |
| **Upper Stopband** | 5.373 GHz – 7.600 GHz | Insertion Loss (IL) | > 45 dB |

This image contains the circuit schematic, substrate properties, and the resulting frequency response (S-parameters) using the stub technique.
<img width="1023" height="470" alt="image" src="https://github.com/user-attachments/assets/ad89ea22-f148-40f0-8de1-9140b0d25c13" />

This image displays the physical microstrip geometry and routing of the filter.
<img width="997" height="279" alt="image" src="https://github.com/user-attachments/assets/118530c5-1920-4895-b8fd-381d884f9586" />

## PCB Layout
The physical layout was executed in KiCad. Impedance matching was carefully maintained with a 50-ohm main microstrip feedline spine, terminating in multiple grounding via arrays at the stub ends to minimize parasitic inductance at 3.76 GHz.

Top Board

<img width="787" height="369" alt="image" src="https://github.com/user-attachments/assets/6f56a4f3-f305-4cf7-ae11-eb5e34407d4f" />

Bottom Board

<img width="724" height="403" alt="image" src="https://github.com/user-attachments/assets/22315750-2b0e-4ec6-9b0c-2062e70b386b" />



