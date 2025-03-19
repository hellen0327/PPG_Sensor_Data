# PPG and Glucose Dataset

## 📌 Description  
This repository contains a dataset of photoplethysmography (PPG) signals recorded from three different locations (forehead, ear, and fingertip), along with **fixed parameters** such as age, gender, and blood glucose levels.

**Photoplethysmography (PPG)** is a low-cost, non-invasive technique that measures peripheral blood flow variations by illuminating a body region (e.g., the fingertip) and detecting fluctuations in reflected or transmitted light caused by blood volume changes in the microvascular tissue. This dataset is particularly useful for research in **non-invasive blood glucose monitoring**, as **blood glucose** refers to the concentration of glucose in the bloodstream, a key biomarker for diabetes management. Normal fasting glucose levels range between 70 and 100 mg/dL, and alternative methods like PPG are being explored to estimate glucose levels without requiring invasive blood samples (Argüello-Prada & Bolaños, 2023).  

## 📊 Dataset Structure  
The dataset consists of processed `.CSV` files (comma-separated-value format) containing PPG signals and fixed parameters for a total of **23 subjects**. Each file corresponds to an individual recording session, with a **duration of 120 seconds per trial**. The dataset is organized into two main folders:  

- **ppg_csv/** → Contains `.CSV` files with PPG signals recorded from three different locations (forehead, ear, and fingertip).  
- **fixed_parameters/** → Contains `.TXT` files summarizing the fixed parameters for each subject, including age, gender, and blood glucose level.

## 📁 Data Format 
All files follow the naming convention: 
- Sujeto_##.csv
- Sujeto_##.txt
where `##` represents the subject number (e.g., `Sujeto_01.csv`, `Sujeto_01.txt`).  

### **PPG Data (`ppg_csv/`)**  
Each `.CSV` file (comma-separated-value format) contains the following columns:  
- **Time (s):** Timestamp of the recording.  
- **PPG_Forehead:** PPG signal recorded from the forehead.  
- **PPG_Ear:** PPG signal recorded from the ear.  
- **PPG_Fingertip:** PPG signal recorded from the fingertip.

### **Fixed Parameters (`fixed_parameters/`)**  
Each `.TXT` file contains a summary of the subject's fixed parameters, including:  
- **Subject ID:** Sujeto_##  
- **Signals:** PPG_Forehead; PPG_Ear; PPG_Fingertip  
- **Age:** Subject's age.  
- **Gender:** Subject's gender (`M` for male, `F` for female).   
- **Glucose Level (mg/dL):** Blood glucose measurement at the time of the recording.

## 📄 Reference  
Argüello-Prada, E. J., & Bolaños, S. M. (2023). *On the role of perfusion index for estimating blood glucose levels with ultrasound-assisted and conventional finger photoplethysmography in the near-infrared wavelength range*. **Biomedical Signal Processing and Control, 86**, 105338.  
[https://doi.org/10.1016/j.bspc.2023.105338](https://doi.org/10.1016/j.bspc.2023.105338)
