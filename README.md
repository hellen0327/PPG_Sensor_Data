# PPG and Glucose Dataset

## 📌 Description  
This repository contains a dataset of photoplethysmography (PPG) signals recorded from three different locations (forehead, ear, and fingertip), along with patient metadata including age, gender, and blood glucose levels.  

**Photoplethysmography (PPG)** is a low-cost, non-invasive technique that measures peripheral blood flow variations by illuminating a body region (e.g., the fingertip) and detecting fluctuations in reflected or transmitted light caused by blood volume changes in the microvascular tissue. This dataset is particularly useful for research in **non-invasive blood glucose monitoring**, as **blood glucose** refers to the concentration of glucose in the bloodstream, a key biomarker for diabetes management. Normal fasting glucose levels range between 70 and 100 mg/dL, and alternative methods like PPG are being explored to estimate glucose levels without requiring invasive blood samples.  

## 📊 Dataset Structure  
The dataset consists of processed `.CSV` files containing PPG signals and corresponding patient metadata. Each file corresponds to an individual recording session. Additionally, `.TXT` files provide metadata summaries for each subject.  

## 📁 Data Format  
Each `.CSV` file contains:  
- **Time (s):** Timestamp of the recording.  
- **PPG_Forehead:** PPG signal recorded from the forehead.  
- **PPG_Ear:** PPG signal recorded from the ear.  
- **PPG_Fingertip:** PPG signal recorded from the fingertip.  
- **Age:** Subject's age.  
- **Gender:** Subject's gender (`M` for male, `F` for female).  
- **Glucose Level (mg/dL):** Blood glucose measurement at the time of the recording.  
