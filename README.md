# EXPERIMENT NO. 4 – HALF WAVE AND FULL WAVE BRIDGE RECTIFIERS

| **Name: Sastharajan P** | | **Reg. No.: 26009606** | |
|---|---|---|---|
| **Date: 24 / 11 / 2026** | | **Batch / Section: AIML** | |

---

## AIM

To study the half wave and full wave bridge rectifiers with and without filter and to observe their input and output waveforms using Proteus.

## COMPONENTS AND EQUIPMENT REQUIRED

| S. No. | Components / Equipment |
|:---:|:---|
| 1 | Diodes |
| 2 | Resistor (load) |
| 3 | Capacitors (filter) |
| 4 | Step-down transformer |
| 5 | Voltmeter |
| 6 | Ammeter |
| 7 | Breadboard |
| 8 | CRO |
| 9 | Connecting wires |
| 10 | Simulation software – Proteus Design Suite |

## THEORY

A rectifier changes AC to DC and is an essential part of a power supply. The unique property of a diode, permitting current to flow in only one direction, is utilised in rectifiers.

### Half wave rectifier

Mains supply is applied to the primary of the step-down transformer. All the positive half cycles of the stepped-down AC supply pass through the diode and all the negative half cycles are eliminated. The peak value of the output voltage is less than the peak value of the input voltage by about 0.6 V because of the voltage drop across the diode. For a half wave rectifier, **Vrms = Vm/2** and **Vdc = Vm/π**, where Vrms is the RMS value of the output, Vdc is the average value of the output and Vm is the peak value of the output.

### Full wave bridge rectifier

During the positive half cycle of the secondary voltage, diodes D1 and D3 are forward biased and D2 and D4 are reverse biased, so current flows through the secondary winding, D1, the load resistor and D3. During the negative half cycle, D2 and D4 are forward biased and D1 and D3 are reverse biased, so current flows through the secondary winding, D2, the load resistor and D4. In both half cycles the current through the load resistor is in the same direction. The peak output voltage is less than the peak input voltage by about 1.2 V due to the drop across two diodes. For a full wave bridge rectifier, **Vrms = Vm/√2** and **Vdc = 2Vm/π**.

### Filters

All rectifier outputs contain a considerable amount of ripple in addition to the DC component. To remove the AC components, a filter is connected at the output of the rectifier. Capacitor input, choke input, RC, CRC, LC and CLC filters are commonly used; the capacitor input filter is the simplest and cheapest. A high-value capacitor C is connected in shunt with the load resistor RL. The capacitor charges to the peak voltage when a half cycle appears at the output. After the peak, the capacitor discharges slowly through RL, since the diode is reverse biased by the capacitor voltage. Before the capacitor voltage drops substantially, the next output cycle arrives and the capacitor recharges to the peak.

## PROCEDURE

1. Wire up the half wave rectifier circuit without capacitor after testing all the components.
2. Switch on the mains supply. Observe the transformer secondary voltage waveform and the output voltage waveform across the load resistor simultaneously on the CRO.
3. Connect the capacitor filter across the load and observe the waveforms. Repeat for different capacitor values.
4. Repeat the above steps for the full wave bridge rectifier.
5. Simulate both rectifiers, with and without filter, in Proteus and capture the input and output waveforms on the virtual oscilloscope.

## CIRCUIT DIAGRAMS

### Half wave rectifier without filter
<img width="570" height="332" alt="image" src="https://github.com/user-attachments/assets/315d912d-c8c4-4375-aaf5-f53b4c18c942" />
**Figure 1:** Half wave rectifier without filter
<img width="980" height="500" alt="image" src="https://github.com/user-attachments/assets/c140c642-1417-4f90-b737-09d325a5daae" />
### Circuit
<img width="1600" height="896" alt="image" src="https://github.com/user-attachments/assets/5831e186-484c-44c5-abf8-34599e95d580" />

### Half wave rectifier with filter
<img width="575" height="308" alt="image" src="https://github.com/user-attachments/assets/52426917-8472-418b-99d8-8d04b0434c59" />

**Figure 2:** Half wave rectifier with filter
<img width="971" height="503" alt="image" src="https://github.com/user-attachments/assets/8136258f-be51-4bc1-9bd7-b955977e808e" />
### Circuit
<img width="1600" height="951" alt="image" src="https://github.com/user-attachments/assets/22069d45-4427-4af5-b031-3a6057c795b7" />
### Model graph
<img width="358" height="317" alt="image" src="https://github.com/user-attachments/assets/0c9d0bdf-8e3d-49da-91ac-78307cea7b21" />
### Tabular 
<img width="1280" height="622" alt="image" src="https://github.com/user-attachments/assets/21c88096-997a-48e2-9565-dfcc3af2186e" />

### Full wave bridge rectifier without filter

<img width="523" height="332" alt="image" src="https://github.com/user-attachments/assets/b3214af6-4bfd-432e-8fee-14008e30ff7c" />

**Figure 3:** Full wave bridge rectifier without filter

<img width="982" height="507" alt="image" src="https://github.com/user-attachments/assets/9035d790-47be-42ad-a204-04754797e792" />
### Circuit
<img width="1600" height="829" alt="image" src="https://github.com/user-attachments/assets/e05bd0e0-3063-4433-8e65-b19655b02366" />

### Full wave bridge rectifier with filter

<img width="531" height="292" alt="image" src="https://github.com/user-attachments/assets/6e5f9503-700d-473b-9716-6b1fdcf961ba" />

**Figure 4:** Full wave bridge rectifier with filter

<img width="983" height="501" alt="image" src="https://github.com/user-attachments/assets/8a07c0e2-9bcd-449f-8f7e-3dd1600d72c5" />
### Circuit
<img width="1600" height="847" alt="image" src="https://github.com/user-attachments/assets/f1864918-0f53-4362-9b60-c11bedebc160" />
### Tabular
<img width="1600" height="680" alt="image" src="https://github.com/user-attachments/assets/1ac2f8f5-db82-469e-8cb1-c580922ab4b5" />

### Model Graph
<img width="1600" height="1449" alt="image" src="https://github.com/user-attachments/assets/825b2d6c-5740-45bb-998b-1598f28cde21" />

## FORMULAE

### A. Half wave rectifier

- Average (DC) voltage: **Vdc = Vm / π**
- Average (DC) current: **Idc = Im / π**
- RMS voltage: **Vrms = Vm / 2**
- RMS current: **Irms = Im / 2**
- Ripple factor: **γ = √[(Vrms / Vdc)² − 1] = 1.21**
- Rectification efficiency: **η = Pdc / Pac × 100 = (Idc² RL) / (Irms² RL) × 100 = 40.6 %**
- Form factor: **FF = Vrms / Vdc = 1.57**
- Peak factor: **PF = Vm / Vrms = 2**
- Peak inverse voltage: **PIV = Vm**

### B. Full wave bridge rectifier

- Average (DC) voltage: **Vdc = 2Vm / π**
- Average (DC) current: **Idc = 2Im / π**
- RMS voltage: **Vrms = Vm / √2**
- RMS current: **Irms = Im / √2**
- Ripple factor: **γ = √[(Vrms / Vdc)² − 1] = 0.482**
- Rectification efficiency: **η = Pdc / Pac × 100 = (Idc² RL) / (Irms² RL) × 100 = 81.2 %**
- Form factor: **FF = Vrms / Vdc = 1.11**
- Peak factor: **PF = Vm / Vrms = √2 = 1.414**
- Peak inverse voltage: **PIV = Vm**

### C. With capacitor filter

- Half wave: **γ = 1 / (2√3 f C RL)**
- Full wave bridge: **γ = 1 / (4√3 f C RL)**

### D. Regulation

- **% Regulation = (VNL − VFL) / VFL × 100**

Vm – peak output voltage; Im – peak load current (Im = Vm / RL); RL – load resistance; f – supply frequency (50 Hz); C – filter capacitance; VNL – no-load voltage; VFL – full-load voltage.

## RESULT

Thus, the input and output waveforms of the half wave and full wave bridge rectifiers with and without filter were observed using Proteus.
