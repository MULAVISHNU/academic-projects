# academic-projects

Welcome to my projects portfolio. This repository serves as a centralized archive of comprehensive project reports, and technical documentation

<<<<<<< HEAD
### 1. Secure Wireless Controller for Handheld Operator of Traffic Control System
=======
# 1. Secure Wireless Controller for Handheld Operator of Traffic Control System
>>>>>>> 5843994f1b273c4f317c35c655b42fe40b549fa5

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

<<<<<<< HEAD
=======

# 2 Reversible Data Hiding Based on Interpolation Techniques

>>>>>>> 5843994f1b273c4f317c35c655b42fe40b549fa5
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

<<<<<<< HEAD
✔ Improved embedding capacity using interpolation

✔ High PSNR and SSIM values

=======
>>>>>>> 5843994f1b273c4f317c35c655b42fe40b549fa5
---

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
<<<<<<< HEAD
- Deep Learning-based reversible data hiding
- GPU acceleration
- Real-time implementation

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


