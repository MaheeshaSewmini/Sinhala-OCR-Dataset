# Sinhala Handwritten OCR Dataset

## Overview
This dataset contains Sinhala handwritten **characters, words, and paragraphs** collected for the research titled: Development of a Vision Transformer-Based OCR System for Sinhala Handwritten Text Recognition. It is designed to support the development and evaluation of machine learning and deep learning models for handwritten text recognition.

---

## Dataset Statistics
The dataset consists of:
- **21,337 characters**
- **3,811 words**
- **368 paragraphs**

**Total: 25,516 scanned images**

---

## Data Collection
The dataset was collected from **381 individuals** using a convenience sampling method to ensure diversity in handwriting styles across different demographic backgrounds.

To capture variation in handwriting, participants were included from different age groups and backgrounds.

---

## Participant Categorization
Participants were categorized into four groups based on a combined classification of education and occupation:

- **Student** – School students  
- **Higher Education** – Individuals pursuing university or other advanced studies  
- **Working** – Individuals engaged in writing-related occupations (e.g., teaching, office work)  
- **Non-working** – Individuals not regularly engaged in writing activities  

---

## Demographic Metadata
Demographic information was recorded separately in an Excel file (`MetaData.xlsx`) using participant IDs to ensure anonymity. The recorded attributes include:

- Age  
- Gender  
- Residential background (rural/urban)  
- Education / Occupation
- Dominant hand (left/right)

Each participant was assigned a unique ID to link metadata with handwritten samples without revealing personal identities.

---

## Ethical Considerations
- Participation in the study was **voluntary**  
- Each participant signed a **consent form** prior to data collection  
- No personally identifiable information (e.g., names) was collected  
- All data was anonymized using participant IDs  
- Metadata was stored separately from image data to ensure confidentiality  

---

## Data Acquisition
All handwritten sheets were scanned at **300 DPI** to ensure high-quality image capture. The scanned images were saved in **JPEG format** for further processing and model training.

---

## Dataset Split
The dataset was divided into:

- **Training set (80%)**
- **Validation set (10%)**
- **Test set (10%)**

This split ensures proper model training, validation, and evaluation without data leakage.

---

## Data Augmentation
Data augmentation was applied **only to the training set** to improve model generalization and prevent data leakage.

- Original training set: **20,365 images**
- 75% of training images were selected for augmentation

### Augmentation Techniques:
- **Rotation**
  - 30% rotated by +5°  
  - 30% rotated by −5°  

- **Thickness variation**
  - 20% increased stroke thickness  
  - 20% decreased stroke thickness  

These transformations were inspired by ThickOCR and ThinOCR techniques (Mahendran, 2023).

**Final training dataset size after augmentation: 35,638 images**

---

## Metadata File
The dataset includes a `metadata.xlsx` file that:
- Links each image to its corresponding label  
- Stores demographic information using participant IDs  
- Supports dataset filtering and analysis  

---

## Intended Use
This dataset is intended for:
- Development of a Vision Transformer-Based OCR System for Sinhala Handwritten Text Recognition research  
- Handwritten text recognition  
- Deep learning and machine learning model development  

---

## License
This dataset is released under the  
**Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

---

## Author
R.M. Maheesha Sewmini Rathnayaka
