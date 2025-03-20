# PPG and Glucose Dataset

## 📌 Description  
This repository contains a dataset of photoplethysmography (PPG) signals recorded from three different locations (forehead, ear, and fingertip), along with **fixed parameters** such as age, gender, and blood glucose levels.

**Photoplethysmography (PPG)** is a low-cost, non-invasive technique that measures peripheral blood flow variations by illuminating a body region (e.g., the fingertip) and detecting fluctuations in reflected or transmitted light caused by blood volume changes in the microvascular tissue. This dataset is particularly useful for research in **non-invasive blood glucose monitoring**, as **blood glucose** refers to the concentration of glucose in the bloodstream, a key biomarker for diabetes management. Normal fasting glucose levels range between 70 and 100 mg/dL, and alternative methods like PPG are being explored to estimate glucose levels without requiring invasive blood samples (Argüello-Prada & Bolaños, 2023).  

## 📊 Dataset Structure  
The dataset consists of processed `.CSV` files (comma-separated-value format) containing PPG signals and fixed parameters for a total of **23 subjects**. Each file corresponds to an individual recording session, with a **duration of 120 seconds per trial**. The dataset is organized into two main folders:  

- **ppg_csv/** → Contains `.CSV` files with PPG signals recorded from three different locations (forehead, ear, and fingertip).  
- **fix_par/** → Contains `.TXT` files summarizing the fixed parameters for each subject, including age, gender, and blood glucose level.

## 📁 Data Format 
All files follow the naming convention: 
- Sujeto_##.csv
- Sujeto_##.txt
  
where `##` represents the subject number (e.g., `Sujeto_01.csv`, `Sujeto_01.txt`).  

### **PPG Data (`ppg_csv/`)**  
Each `.CSV` file contains the following columns:  
- **Time(s):** Timestamp of the recording.  
- **PPG_Forehead:** PPG signal recorded from the forehead.  
- **PPG_Ear:** PPG signal recorded from the ear.  
- **PPG_Fingertip:** PPG signal recorded from the fingertip.

### **Fixed Parameters (`fix_par/`)**  
Each `.TXT` file contains a summary of the subject's fixed parameters, including:  
- **Subject ID:** Sujeto_##  
- **Signals:** PPG_Forehead; PPG_Ear; PPG_Fingertip
- **Sampling Frequency:** Varies per subject
- **Age:** Subject's age.  
- **Gender:** Subject's gender (`M` for male, `F` for female).   
- **Glucose Level (mg/dL):** Blood glucose measurement at the time of the recording.

## 📄 Reference  
Argüello-Prada, E. J., & Bolaños, S. M. (2023). *On the role of perfusion index for estimating blood glucose levels with ultrasound-assisted and conventional finger photoplethysmography in the near-infrared wavelength range*. **Biomedical Signal Processing and Control, 86**, 105338. [https://doi.org/10.1016/j.bspc.2023.105338](https://doi.org/10.1016/j.bspc.2023.105338)

## 📥 Download  
To download the complete dataset, click the link below:  

🔗 **[Download PPG_Sensor_Data.zip](https://github.com/hellen0327/PPG_Sensor_Data/releases/download/v1.0/PPG_Sensor_Data.zip)**  

You can download individual subject files from the links below:  

| Subject | PPG Data (.CSV) | Fixed Parameters (.TXT) |
|---------|----------------|-------------------------|
| 1      | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_1.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_1.txt) |
| 2      | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_2.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_2.txt) |
| 3      | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_3.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_3.txt) |
| 4      | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_4.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_4.txt) |
| 5      | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_5.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_5.txt) |
| 6      | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_6.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_6.txt) |
| 7      | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_7.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_7.txt) |
| 8      | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_8.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_8.txt) |
| 9      | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_9.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_9.txt) |
| 10     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_10.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_10.txt) |
| 11     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_11.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_11.txt) |
| 12     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_12.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_12.txt) |
| 13     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_13.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_13.txt) |
| 14     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_14.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_14.txt) |
| 15     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_15.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_15.txt) |
| 16     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_16.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_16.txt) |
| 17     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_17.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_17.txt) |
| 18     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_18.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_18.txt) |
| 19     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_19.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_19.txt) |
| 20     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_20.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_20.txt) |
| 21     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_21.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_21.txt) |
| 22     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_22.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_22.txt) |
| 23     | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/ppg_csv/Sujeto_23.csv) | [Download](https://github.com/hellen0327/PPG_Sensor_Data/blob/main/fix_par/Sujeto_23.txt) |
