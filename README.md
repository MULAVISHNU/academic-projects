# academic-projects

Welcome to my projects portfolio. This repository serves as a centralized archive of comprehensive project reports, and technical documentation


# 1. Secure Wireless Controller for Handheld Operator of Traffic Control System

A secure, Arduino‑based wireless system that allows authorized traffic police to manually control traffic signals during peak hours. The system integrates fingerprint authentication, IR communication, and an automated barrier mechanism to improve traffic flow and prevent signal jumping.

---

## Features

- **Fingerprint Authentication**  
  Only authorized personnel can operate the controller.
- **Wireless Signal Control**  
  IR‑based remote switches Red/Yellow/Green lights from 50–80 ft.
- **Automated Barrier System**  
  Barrier rises on Red and lowers on Yellow/Green.
- **Energy‑Efficient Design**  
  Low‑power components suitable for portable field use.
- **Manual Override for Peak Hours**  
  Helps traffic police manage unpredictable congestion.
---

## 📡 System Architecture

1. User authenticates via fingerprint.  
2. IR remote sends encoded commands to the controller.  
3. Controller updates traffic lights and barrier position.  
4. System ensures secure and reliable manual control.

---

## 💻 Software

- Arduino IDE  
---

## 📈 Results

- Secure fingerprint‑based access  
- Stable wireless communication  
- Accurate signal switching  
- Smooth barrier operation  
- Fully functional prototype

---

## 📚 Future Improvements

- GSM/WiFi‑based long‑range control  
- Mobile app integration  
- Real‑time traffic analytics  
- Solar‑powered controller

---
## Author

**Sunkari Mula Vishnu Veeranjan**  
[*([Mula Sunkari](https://github.com/MULAVISHNU))*]
# 2 Reversible Data Hiding Based on Interpolation Techniques

=======

# 2 Reversible Data Hiding Based on Interpolation Techniques

A MATLAB-based implementation of a **Reversible Data Hiding (RDH)** scheme that securely embeds a secret image into a cover image using **image interpolation** and **pixel permutation techniques**. The proposed method enables the complete recovery of both the original cover image and the hidden secret image without any permanent distortion.

---

## Features

### Reversible Data Hiding
- Embeds secret image data into a cover image.
- Recovers both the secret image and original cover image perfectly.

### Image Interpolation
- Enlarges the cover image using interpolation before embedding.
- Improves embedding capacity while maintaining image quality.

### Pixel Permutation
- Uses pixel permutation tables to securely hide data.
- Enhances resistance against unauthorized extraction.

### High Image Quality
- Preserves visual quality of the stego image.
- Achieves high PSNR and SSIM values.

### Secure Information Hiding
- Suitable for confidential image transmission.
- Resistant to statistical attacks due to histogram preservation.

---

## System Workflow

1. Load the cover image.
2. Scale down and interpolate the image.
3. Convert the secret image into binary data.
4. Split the binary stream into **5-bit** and **1-bit** groups.
5. Perform pixel manipulation based on the extracted bit.
6. Rearrange pixels according to the permutation table.
7. Generate the final stego image.
8. At the receiver, recover:
   - Original cover image
   - Hidden secret image

---



## Technologies Used

- MATLAB
- Digital Image Processing
- Reversible Data Hiding (RDH)
- Image Interpolation
- Pixel Permutation
- Steganography

---

## Performance

The proposed algorithm provides:

- High embedding capacity
- High visual image quality
- Accurate extraction of hidden data
- Complete recovery of the original cover image
- Histogram-preserving embedding for improved security

---

## MATLAB Modules

### Data Embedding
- Cover image preprocessing
- Image interpolation
- Secret image binary conversion
- Pixel manipulation
- Pixel permutation
- Stego image generation

### Data Extraction
- Block reconstruction
- Pixel restoration
- Secret data extraction
- Original image recovery

---

## Project Structure

```
├── DataEmbedding.m
├── DataExtraction.m
├── Images
│   ├── Cover Image
│   ├── Secret Image
│   ├── Stego Image
│   ├── Recovered Cover Image
│   └── Extracted Secret Image
├── Results
├── Documentation
│   └── Project Report.pdf
└── README.md
```

---

## Results

✔ Secure image-based information hiding

✔ Lossless recovery of the original image

✔ Accurate extraction of hidden data



## Applications

- Secure Cloud Storage
- Medical Image Protection
- Military Communications
- Digital Forensics
- Copyright Protection
- Confidential Document Sharing

---

## Future Improvements

- Adaptive interpolation algorithms
- Color image support
- Multi-image embedding


## Author

**Sunkari Mula Vishnu Veeranjan**  
[*([Mula Sunkari](https://github.com/MULAVISHNU))*]
---





# 3.Hybrid Linkwitz–Riley 4 Crossover Filter Design

A complete analog IC design project implementing a **4th-order Linkwitz–Riley (LR4) active crossover filter** using a **custom-designed Two-Stage Miller Operational Transconductance Amplifier (OTA)**. The project covers behavioral modeling, transistor-level circuit design, gm/Id-based sizing, filter integration, simulation, and verification using the **IHP SG13G2 open-source PDK**.

---

## Features

### 🎛️ Linkwitz–Riley LR4 Filter
- Designed a fourth-order active crossover filter.
- Flat summed frequency response.
- 10 kHz crossover frequency.
- Butterworth response with **Q = 0.707**.

### ⚡ Two-Stage Miller OTA
- Custom transistor-level OTA design.
- Miller compensation with zero-nulling resistor.
- High DC gain with improved phase margin.
- Optimized using the **gm/Id methodology**.

### 📊 Behavioral & Transistor-Level Design
- LTspice behavioral model.
- Xschem transistor implementation.
- Open-source IHP SG13G2 PDK.

### 📈 Circuit Optimization
- gm/Id sizing methodology.
- Industrial device sizing.
- Compensation capacitor optimization.
- Stability enhancement using pole-splitting.

### ✅ Design Verification
- AC Analysis
- Transient Analysis
- Noise Analysis
- PVT Corner Analysis
- Monte Carlo Simulation

---


## Workflow

1. Define filter specifications.
2. Develop the LTspice behavioral model.
3. Design the 5-Transistor OTA.
4. Extend to a Two-Stage Miller OTA.
5. Size transistors using the gm/Id methodology.
6. Implement the design in Xschem.
7. Integrate the OTA into a Sallen-Key filter.
8. Cascade two Butterworth stages to form an LR4 crossover.
9. Perform AC, transient, and noise simulations.
10. Validate robustness using PVT and Monte Carlo analyses.

---

## Technologies Used

- Xschem
- LTspice
- ngspice
- Python
- Jupyter Notebook
- gm/Id Methodology
- IHP SG13G2 Open PDK
- CACE
- Analog IC Design

---

## Project Structure

```text
├── Behavioural Model
│   ├── LTspice Schematic
│   └── AC Analysis
│
├── OTA Design
│   ├── 5T OTA
│   ├── Two-Stage Miller OTA
│   ├── gmId Sizing Notebook
│   └── Xschem Schematics
│
├── Filter Design
│   ├── Sallen-Key LPF
│   ├── Linkwitz-Riley LPF
│   └── Linkwitz-Riley HPF
│
├── Simulation
│   ├── AC Analysis
│   ├── Transient Analysis
│   ├── Noise Analysis
│   ├── PVT Analysis
│   └── Monte Carlo Analysis
│
├── Documentation
│   └── Development Report
│
└── README.md
```

---

## Performance

### OTA Performance

- Open-Loop Gain: **65.9 dB**
- Target Gain: **≥ 60 dB**
- Predicted UGBW: **24.82 MHz**
- Target Bandwidth: **10 MHz**
- Core Current: **27 μA**
- Power Dissipation: **72.85 μW**

### Filter Performance

- Filter Type: Linkwitz–Riley 4th Order
- Cutoff Frequency: **10 kHz**
- Quality Factor (Q): **0.707**
- Flat crossover response
- Stable phase characteristics

---

## Simulation Results

The design was validated through:

- Small-Signal AC Analysis
- Frequency Response
- Phase Response
- Step Response
- Noise Analysis
- Pole Stability Verification
- Process Corner Analysis
- Voltage Sweep
- Temperature Sweep
- Monte Carlo Mismatch Analysis

---

## Applications

- Active Loudspeaker Crossovers
- Professional Audio Systems
- Hi-Fi Audio Amplifiers
- Studio Monitors
- Embedded Audio Electronics
- Analog Signal Conditioning
- Mixed-Signal Integrated Circuits

---

## Future Improvements

- Fully integrated IC layout implementation
- Layout versus schematic (LVS) verification
- Post-layout parasitic extraction
- Power optimization
- Higher bandwidth OTA architectures
- Fully differential OTA implementation
- Automatic analog synthesis using optimization algorithms

---

## Authors

**Sriram Repaka**

Hochschule Bremen

**Mula Vishnu Sunkari**

Hochschule Bremen

---


# 4. Low Noise Amplifier (LNA) Design Using Microstrip Line Technology

A microwave circuit design project implementing a **4.5 GHz Low Noise Amplifier (LNA)** using **microstrip line technology** on a **Rogers RO4003C substrate**. The amplifier is designed around the **Infineon BFP640 bipolar transistor**, with impedance matching achieved through Smith Chart analysis and distributed microstrip matching networks. The complete workflow includes theoretical calculations, transmission-line design, full-wave simulation in **AWR Microwave Office**, PCB fabrication, and experimental validation using a Vector Network Analyzer (VNA).

---

## Features

### 📡 4.5 GHz Low Noise Amplifier
- Designed for RF front-end applications operating near **4.5 GHz**.
- Achieves a peak transducer gain of **15.6 dB**.
- Bandwidth exceeding **100 MHz**.

### 📐 Microstrip Matching Network
- Input and output matching using distributed microstrip lines.
- Smith Chart-based impedance matching.
- Conversion of lumped matching networks to microstrip structures.

### ⚙️ Stable Amplifier Design
- Unconditionally stable across the operating frequency.
- Proper source and load impedance matching.
- Optimized return loss below **−15 dB**.

### 🧪 Simulation & Experimental Validation
- Circuit designed and optimized in **AWR Microwave Office**.
- PCB fabricated and tested using a **Vector Network Analyzer (VNA)**.
- Measured results closely match theoretical and simulated performance.

---

## Workflow

1. Obtain transistor S-parameters at **4.5 GHz**.
2. Calculate source and load reflection coefficients (ΓS and ΓL).
3. Design impedance matching networks using the Smith Chart.
4. Convert lumped matching networks into microstrip transmission lines.
5. Simulate the amplifier using **AWR Microwave Office**.
6. Design the PCB layout with microstrip technology.
7. Fabricate and assemble the amplifier.
8. Measure S-parameters using a Vector Network Analyzer.
9. Compare measured results with simulation.

---

## Technologies Used

- AWR Microwave Office
- TXLINE
- Smith Chart
- Rogers RO4003C Substrate
- Microstrip Line Technology
- RF PCB Design
- Vector Network Analyzer (VNA)
- Microwave Circuit Design

---

## Hardware Components

- Infineon BFP640 Bipolar RF Transistor
- Rogers RO4003C PCB
- RF Transmission Lines
- Open-Circuit Microstrip Stubs
- DC Bias Network
- Passive RF Components
- SMA Connectors

---

## Project Structure

```text
├── Design Calculations
│   ├── S-Parameter Analysis
│   ├── Smith Chart Design
│   ├── Reflection Coefficient Calculations
│   └── Transmission Line Dimensions
│
├── Simulation
│   ├── AWR Schematic
│   ├── Transmission Line Model
│   ├── Microstrip Layout
│   └── Frequency Response
│
├── PCB Design
│   ├── Layout
│   ├── Fabrication
│   └── Assembly
│
├── Experimental Validation
│   ├── VNA Measurements
│   ├── Gain Analysis
│   └── Result Comparison
│
├── Documentation
    └── Project Report.pdf

```

---

## Performance

### RF Performance

| Parameter | Value |
|-----------|------:|
| Operating Frequency | **4.5 GHz** |
| Peak Gain (S21) | **15.6 dB** |
| Center Frequency | **4499 MHz** |
| Bandwidth | **>100 MHz** |
| Input Return Loss (S11) | **< −15 dB** |
| Output Return Loss (S22) | **< −15 dB** |
| Stability | **Unconditionally Stable** |

---

## Simulation Results

The amplifier was validated through:

- ✅ S-Parameter Analysis
- ✅ Gain (S21)
- ✅ Input Matching (S11)
- ✅ Output Matching (S22)
- ✅ Frequency Sweep
- ✅ Bandwidth Analysis
- ✅ Stability Verification
- ✅ Microstrip Layout Simulation

---

## Experimental Validation

The fabricated PCB was tested using:

- Vector Network Analyzer (VNA)
- 5 V DC Bias Supply
- RF Measurement Setup

Experimental measurements confirmed:

- Peak gain near **15.6 dB**
- Center frequency around **4.5 GHz**
- Bandwidth greater than **100 MHz**
- Excellent agreement between theoretical, simulated, and measured results

---

## Applications

- RF Front-End Receivers
- Satellite Communication
- Wireless Communication Systems
- Radar Systems
- IoT RF Modules
- Microwave Instrumentation
- Signal Reception Systems

---

## Future Improvements

- Multi-band LNA design
- Lower noise figure optimization
- MMIC implementation
- Higher-frequency operation (5G/mmWave)
- Automatic impedance matching
- Thermal optimization
- Integrated RF front-end module

---

## Results

- ✔ Designed a **4.5 GHz Low Noise Amplifier** using microstrip technology.
- ✔ Achieved **15.6 dB peak transducer gain**.
- ✔ Obtained bandwidth exceeding **100 MHz**.
- ✔ Achieved input and output return losses below **−15 dB**.
- ✔ Verified unconditional stability.
- ✔ Successfully fabricated and experimentally validated the PCB prototype.

---

## Authors

**Mula Vishnu Veeranjan Sunkari**  
Hochschule Bremen

**Aditya Rao**  
Hochschule Bremen

**Anagha Varghese**  
Hochschule Bremen