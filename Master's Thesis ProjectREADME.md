# PCB-tiny-defects-detections
 The goal of this project is to accurately identify and classify different types of defects on PCBs, such as spurious copper, mouse bite, open circuit, missing hole, spur, and short.  the process of detecting defects on Printed Circuit Boards (PCBs) using the YOLOv8 and YOLOv9 object detection model.
# PCB Defect Detection Using Deep Learning

## 🎓 Master’s Thesis Project
This repository contains my Master’s thesis, **awarded a Distinction**, focusing on advanced deep learning approaches for PCB defect detection.
### Title
**PCB Defect Detection Using YOLOv8 and YOLOv9**

### Author
Maimoona  Butt

### Degree
Master’s Thesis (DATA SCIENCE) 

### Academic Year
2023–2024  

---

## Abstract
This research focuses on the detection and identification of defects on printed circuit boards (PCBs) with high precision using advanced deep learning techniques. Traditional manual inspection methods for PCB defect detection are often inefficient, time-consuming, and prone to inaccuracies, particularly when dealing with complex defect types or varying environmental conditions.

To address these limitations, this study employs two state-of-the-art object detection models, **YOLOv8** and **YOLOv9**, to identify six distinct categories of PCB defects. The methodology includes comprehensive data preprocessing, data augmentation, model training, and performance evaluation using key metrics such as box loss, classification (CLS) loss, distribution focal loss (DFL), and mean average precision (mAP).

The experimental results demonstrate that both models achieve high detection accuracy; however, YOLOv8 consistently outperforms YOLOv9 by achieving a slightly higher mAP score and lower classification loss. These results suggest that YOLOv8 is more suitable for high-precision PCB defect detection tasks.

Potential challenges such as model bias, environmental variability, computational cost, and model drift are identified. Strategies to mitigate these risks are proposed to enhance robustness and real-world applicability. Overall, this research contributes to the advancement of intelligent inspection systems by demonstrating the effectiveness of modern deep learning models in industrial PCB defect detection.

---

## Research Objectives
- To detect and classify multiple PCB defect types using deep learning
- To evaluate and compare the performance of YOLOv8 and YOLOv9
- To analyze loss functions and detection accuracy metrics
- To assess the feasibility of deploying deep learning-based inspection systems in real-world manufacturing environments

---

##  Methodology
The research methodology consists of the following stages:
1. Dataset preparation and preprocessing
2. Data augmentation to improve generalization
3. Model training using YOLOv8 and YOLOv9
4. Performance evaluation using mAP, box loss, CLS loss, and DFL loss
5. Comparative analysis of model performance
6. Risk identification and mitigation strategy development

---

## Tools & Technologies
- Python
- Deep Learning
- YOLOv8
- YOLOv9
- Computer Vision
- GPU-based model training
- Data augmentation techniques

---

## Repository Structure
- `Thesis.pdf` – Final thesis document
- `Data/` – Dataset used for training and evaluation (restricted if confidential)
- `Code/` – Model training and evaluation scripts
- `Results/` – Performance metrics and visual outputs
- `Figures/` – Detection samples and evaluation plots

---

## Key Findings
- Both YOLOv8 and YOLOv9 achieve high accuracy in PCB defect detection
- YOLOv8 demonstrates superior performance with higher mAP and lower classification loss
- Deep learning-based inspection systems show strong potential for industrial deployment

---

##  Research Contribution
This work advances the field of intelligent manufacturing by:
- Providing a comparative evaluation of modern YOLO architectures for PCB inspection
- Demonstrating the applicability of deep learning in high-precision industrial defect detection
- Offering insights into improving model robustness for real-world manufacturing environments

---

## Disclaimer
This repository is intended for **academic and research purposes only**.  
Commercial use of the models, data, or findings requires prior permission.

---

## Contact
For academic collaboration or research inquiries:  maimoona31oct@gmail.com
**Maimoona BUTT**
