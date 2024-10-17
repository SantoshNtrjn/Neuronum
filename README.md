# Neuronum

## Overview
**Neuronum: Automated Brain Disease Diagnosis and Patient Support System**

**Authors** : *Santosh N, Vani Lavanya A, Sai Shree Ram Balaji B L*

Neuronum is an advanced web application designed to aid in the diagnosis and management of five critical brain disorders: Alzheimer's Disease, Parkinson's Disease, Brain Tumor, Epilepsy, and Stroke. Utilizing state-of-the-art Convolutional Neural Networks (CNN), this system assists radiologists in analyzing MRI scans to accurately detect these conditions.

Check out the paper at [IEEE Xplore](https://ieeexplore.ieee.org/document/10465514).

*This paper was presented at 2023 International Conference on Innovative Computing, Intelligent Communication and Smart Electrical Systems (ICSES)*.

## Abstract
The "Automated Brain Disease Diagnosis and Patient Support System" is a web application that aids hospital administration in the diagnosis of five classes of brain disorders: Alzheimer's Disease, Parkinson's Disease, Brain Tumor, Epilepsy, and Stroke. The application involves radiologists uploading MRI scans for detection through a CNN. After successful diagnosis, the system generates detailed reports with diagnosis results, supportive action measures, patient details, and recommends neuro-specialists. A statistical visualization tool identifies trends in diagnosed brain diseases. Secure OTP-based authentication allows patients to access reports and interact with an AI assistant. React.js is used for the front-end, and Flask, Node.js, Express.js, and MongoDB for the back-end. Various Python libraries and Streamlit are used for email automation, report generation, and data visualization. The system aims to detect a broader spectrum of brain diseases with high accuracy and streamline patient support services, improving healthcare outcomes.

![Neuronum Card](https://github.com/SantoshNtrjn/Neuronum/blob/main/assets/spec_card.png)

## Features
- **MRI Scan Analysis:** Radiologists can upload MRI scans for automated detection of brain diseases.
- **Detailed Diagnostic Reports:** Automatically generated reports include diagnosis results, supportive action measures, patient details, and recommended neuro-specialists.
- **Statistical Visualization Tool:** Integrated with Streamlit to identify trends in diagnosed brain diseases.
- **Secure Patient Access:** OTP-based authentication for patients to access their diagnosis reports and interact with an AI assistant.
- **Email Automation and Report Generation:** Employs various Python libraries for streamlined operations.

## Tech Stack
- **Front-End:** React.js
- **Back-End:** Flask, Node.js, Express.js, MongoDB
- **Visualization:** Streamlit

## System Architecture
![System Architecture](https://github.com/SantoshNtrjn/Neuronum/blob/main/assets/arch.png)

The system's frontend is developed using React.js, while the backend utilizes Flask, Node.js, Express.js, and MongoDB for efficient data handling. Python libraries enable email automation, and Streamlit facilitates statistical data visualization. The proposed system aims to enhance brain disease diagnosis accuracy and streamline patient support services for improved healthcare outcomes. 
The system also utilizes various Python Libraries (smtplib, reportlab, matplotlib, pandas) for email automation and report generation. 

## Results & Performance Analysis
<img src="https://github.com/SantoshNtrjn/Neuronum/blob/main/assets/model_prediction.png" alt="Model Prediction" width="250" height="250"> <img src="https://github.com/SantoshNtrjn/Neuronum/blob/main/assets/performance.png" alt="Performance Analysis" width="550" height="250">

<sub>Model Prediction (Left) & Performance Analysis (Right)<sub>

The 'Automated Brain Disease Diagnosis and Patient Support System' employs a multi-class CNN model with an accuracy rate of 91.3%, elevating brain disease diagnosis accuracy while streamlining patient support.
## Citation
If you found our project helpful, please cite our paper:
```bash
V. L. A, S. N and S. S. R. B. B. L, "Automated Brain Disease Diagnosis and Patient Support System,"
2023 International Conference on Innovative Computing, Intelligent Communication and Smart
Electrical Systems (ICSES), Chennai, India, 2023, pp. 1-7, doi: 10.1109/ICSES60034.2023.10465514.
keywords: {Parkinson's disease;Magnetic resonance imaging;Data visualization;Authentication;
Stroke (medical condition);Market research;Libraries;Brain disease diagnosis;CNN;web application;
patient support;statistical data visualization;secure authentication},
```
## Note
This repository contains the published [IEEE paper](https://ieeexplore.ieee.org/document/10465514) detailing the system architecture, methodology, and results. The source code for the application is not included in this repository.

## Contact
For more information, please refer to the published paper at [IEEE Xplore](https://ieeexplore.ieee.org/document/10465514) or contact via [email](mailto:santoshpn03@gmail.com).
