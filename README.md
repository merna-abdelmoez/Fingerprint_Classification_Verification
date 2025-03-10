# Finger Print Verification and Gender Classification

## Overview
This project aims to develop a deep learning-based system for fingerprint gender classification and verification. The goal is to analyze fingerprint patterns to determine the gender of an individual and verify the identity based on biometric authentication.

## Dataset
We have worked on three datasets:

### 1. Collected Dataset
- **Participants:** 22 individuals (10 male, 12 female).
- **Finger Captured:** Thumb only.
- **Data Size:** 6 instances per person.

### 2. FVC2004 Dataset
- **Databases:** 4 datasets (DB1, DB2, DB3, DB4) collected using diverse technologies.
- **Participants:** 90 Computer Science students (average age: 24).
- **Fingers Captured:** Forefinger and middle finger of both hands (4 fingers total).

### 3. SOCOFING Dataset
- **Dataset Size and Demographics:** Contains 6,000 fingerprints from 600 African subjects, with 10 fingerprints per subject, all aged 18 years or older.
- **Attributes and Labels:** Includes metadata such as gender, hand type, and specific finger name for each fingerprint.
- **Original Fingerprint Acquisition:** Fingerprints were collected using Hamster Plus (HSDU03PTM) and SecuGen SDU03PTM scanners.
- **Image Resolution:** All images have a resolution of 1 × 96 × 103 (grayscale × width × height).

## Methodology
1. **Preprocessing:**
   - Image enhancement techniques such as noise reduction and contrast adjustment.
   - Feature extraction using deep learning models.
2. **Model Development:**
   - Convolutional Neural Networks (CNNs) for gender classification.
   - Siamese Networks for fingerprint verification.
3. **Training & Evaluation:**
   - Performance metrics as accuracy for classification and similarity scores for verification.
4. **Deployment:**
   - Integration into biometric authentication systems.
  
## Results
1.Gender Classification accuracy = 0.9963%

2.Finger Print Recognition accuracy = 0.9%

## Contributors <a name = "Contributors"></a>
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/merna-abdelmoez">
        <img src="https://github.com/merna-abdelmoez.png" width="200px" alt="@MernaAbdelmoez">
        <br>
        <sub><b>Merna AbdElMoez</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Habiba-Mohsen">
        <img src="https://github.com/Habiba-Mohsen.png" width="200px" alt="@HabibaMohsen">
        <br>
        <sub><b>Habiba Mohsen</b></sub>
      </a>
    </td>
  </tr>
</table>


## Acknowledgments
**This project was supervised by Dr. Ahmed Badwy, who provided invaluable guidance and expertise throughout its development as a part of the Biometric Course at Cairo University Faculty of Engineering.**


<div style="text-align: right">
    <img src="https://imgur.com/Wk4nR0m.png" alt="Cairo University Logo" width="100" style="border-radius: 50%;"/>
</div>


