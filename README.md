# AAI521 – AgroPest12 Crop Pest Detection (Group 5)

This repository contains the final project for **MSAAI 521 – Computer Vision**.  
The goal of the project is to build an object detection system capable of identifying **12 agricultural pest species** from real field images using the **AgroPest-12 dataset**.

We developed a full pipeline including:
- Dataset extraction & annotation conversion to YOLO format  
- Exploratory data analysis (EDA)  
- Class imbalance handling (oversampling)  
- Training YOLOv8 models (nano & small variants)  
- Evaluation using mAP, confusion matrices, PR curves  
- Interpretation & error analysis  


## Dataset: AgroPest-12
AgroPest-12 contains:

- **12 pest species**  
- **Train / Valid / Test splits**  
- **YOLO labels** (normalized bounding boxes)

The dataset was used for:
- Object detection  
- Class distribution studies  
- Small-object analysis  
- Image visualization & sample bounding boxes  


## Notebooks (GitHub Links)

### Following notebook contains collective EDA, Modelling, Metrics Analysis and Visualizations

https://github.com/lambcallum-a11y/aai521-agropest-grp5/blob/main/MSAAI_521_agropest_grp5.ipynb



