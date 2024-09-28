# Lab 2 – Observing AC Signals with Capacitors and Inductors


## Student Name: 

---

### 1. Circuit Schematic

**Task 1: Impedance of a Capacitor (Capacitive Reactance)**

- **Circuit Description**: AC 5V source with a 100µF capacitor.
- **Part Numbers**: 100 µF capacitor, AC voltage source (amplitude based on last two digits of student number, my student number last digits are 35 so i will be using 5V).
- **Variable:** 10hz 100hz and 1000hz
- **Input/Output Designations**: Input is AC voltage, and output is voltage across and current through the capacitor.


**Schematic Diagram:**
10hz
![10hz](elelab2_10hz.png) 

**Schematic Diagram:**
100hz
![1000hz](elelab2_100hz.png) 

**Schematic Diagram:**
1000hz
![1000hz](elelab2_1000hz.png) 
---

**Task 2: Impedance of an Inductor (Inductive Reactance)**

- **Circuit Description**: AC voltage source with a 100mH inductor (PCH-45X-107 Coilcraft).
- **Part Numbers**: 100mH inductor, AC voltage source.


**Schematic Diagram:** 
10hz 
![10hz](elelab2_10hz_task2.png) 

**Schematic Diagram:**
100hz
![100hz](elelab2_100hz_task2.png) 

**Schematic Diagram:** 
1000hz
![1000hz](elelab2_1000hz_task2.png) 
---

**Task 3: Frequency Response of Capacitor and Inductor**

- **Circuit Description**: Same circuits as Tasks 1 and 2, but now using AC analysis to observe frequency response.
- **Part Numbers**: 100µF capacitor, 100mH inductor, AC voltage source.


**Schematic Diagram:**
![capacitator](elelab2_task3_capacitator.PNG) 

**Schematic Diagram:**
![inductor](elelab2_task3_inductor.PNG) 

---

**Task 4: Measuring the RC Low-Pass Filter**

- **Circuit Description**: Resistor (10kΩ) and calculated capacitor value to form an RC low-pass filter.
- **Part Numbers**: 10kΩ resistor, calculated capacitor value, PicoScope 2000 signal generator (1V sine wave input).
- **Pin Designations**: Label connections to PicoScope’s output and oscilloscope channels A (input) and B (output).
- **Input/Output Designations**: Input is PicoScope signal, output is measured with the oscilloscope.
- **External Connections**: Connections to the signal generator and oscilloscope.

**Schematic Diagram:**
(Insert schematic of the RC low-pass filter circuit here)

---

### 2. Instruments Used

| Instrument          | Model Number   | Function                                       |
|---------------------|----------------|------------------------------------------------|
| PicoScope 2000      | [Model Number] | Signal generator and oscilloscope              |
| Multimeter          | [Model Number] | Measure voltage and current                    |
| Function Generator  | [Model Number] | Generate AC signals for simulation             |
| Power Supply        | [Model Number] | Provide external power, if necessary           |

---

### 3. Measurements and Observations

#### Task 1: Capacitive Reactance Measurements

| Frequency | Input Voltage (Vin) | Output Voltage (Vout) | Current (I) | Scale (Oscilloscope/Multimeter) | Phase Shift (°) |
|-----------|---------------------|----------------------|-------------|--------------------------------|-----------------|
| 10 Hz     |                     |                      |             |                                |                 |
| 100 Hz    |                     |                      |             |                                |                 |
| 1 kHz     |                     |                      |             |                                |                 |

#### Task 2: Inductive Reactance Measurements

| Frequency | Input Voltage (Vin) | Output Voltage (Vout) | Current (I) | Scale (Oscilloscope/Multimeter) | Phase Shift (°) |
|-----------|---------------------|----------------------|-------------|--------------------------------|-----------------|
| 10 Hz     |                     |                      |             |                                |                 |
| 100 Hz    |                     |                      |             |                                |                 |
| 1 kHz     |                     |                      |             |                                |                 |

#### Task 3: Frequency Response (AC Analysis)

- **Capacitor**: As frequency increases, the current through the capacitor increases.
- **Inductor**: As frequency increases, the current through the inductor decreases.

#### Task 4: RC Low-Pass Filter Measurements

| Frequency | Vin (V) | Vout (V) | Attenuation (dB) | Input Signal Scale (Oscilloscope) | Output Signal Scale (Oscilloscope) |
|-----------|---------|----------|------------------|----------------------------------|-----------------------------------|
| 1.59 kHz  |         |          |                  |                                  |                                   |

---

### 4. Error Analysis

#### Task 1 and 2: Impedance Measurements

- **Uncertainty Sources**: Resolution of the oscilloscope and multimeter, component tolerances (capacitor and inductor), measurement techniques.
  
#### Task 4: RC Low-Pass Filter

- **Uncertainty in Attenuation Measurement**: Errors in measuring the input and output voltage using the oscilloscope.
- **Potential Error Estimate**:  
  - **Expected Attenuation**: [calculated value] dB
  - **Measured Attenuation**: [value] dB
  - **Error Estimate**: +/- [value]

---

### 5. Additional Notes and Conclusions

- **Notes**: Document any unexpected results, troubleshooting steps, or deviations from the original procedure.
- **Conclusions**: Summarize key findings, such as:
  - Capacitive and inductive reactance behavior confirmed.
  - Low-pass filter shows expected frequency response and attenuation at the corner frequency (1.59 kHz).
