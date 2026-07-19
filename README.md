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

---

## 👤 Author

**Sunkari Mula Vishnu Veeranjan**  
[*([Mula Sunkari](https://github.com/MULAVISHNU))*]
