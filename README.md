# **Impact of Adverse Weather and Image Distortions on Vision-Based UAV Detection: A Performance Evaluation of Deep Learning Models**

[![DOI](https://zenodo.org/badge/DOI/10.3390/drones8110638.svg)](https://doi.org/10.3390/drones8110638)


---

## **Abstract**
Unmanned aerial vehicle (UAV) detection in real-time is challenging, particularly under adverse weather. This work evaluates popular deep learning models under various weather and image distortion conditions, including rain, motion blur, and noise. A custom dataset and benchmark study reveal the significant impact of these conditions on UAV detection models (YOLOv5, YOLOv8, Faster-RCNN, RetinaNet, and YOLO-NAS), with performance degrading by up to 77 points in mean average precision (mAP) under severe conditions. This work proposes an enhancement strategy to improve model resilience, achieving substantial mAP improvements under challenging conditions.

---

## **Table of Contents**
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Methodology](#methodology)
- [Results](#results)
- [How to Use](#how-to-use)
- [Acknowledgments](#acknowledgments)

---

## **Introduction**
This project investigates the performance degradation of vision-based UAV detection models under adverse weather and image distortions, including conditions like heavy rain, motion blur, and noise.

---

## **Datasets**

### **Complex Background Dataset (CBD)**
[![Download Complex Background Dataset](https://img.shields.io/badge/Download-Complex%20Background%20Dataset-blue?style=for-the-badge)](https://drive.google.com/file/d/1-BmnQe9LllS7EA4NhGGj-2f7MKZjfnR-/view?usp=sharing)

### **UAV-AWID (UAVs-Adv Weather and Image Distortions)**

- **Rainy Test Dataset (RTSD):**
  - [Drizzle](https://drive.google.com/drive/folders/1tZY-CggDojx5xMS9icmvwH1qBpioTFKt?usp=drive_link)
  - [Heavy](https://drive.google.com/drive/folders/1vhBinTDQmizwLFhyvJHmWZSEFkUs3yKh?usp=drive_link)
  - [Torrential](https://drive.google.com/drive/folders/1_AeAvDs-WiUbtdMD26OeXlv2QUT7okab?usp=drive_link)

- **Motion Blur Test Dataset (MBTD):**
  - [Low](https://drive.google.com/drive/folders/12oAfvrGaa1dz1UW7qFvEUrxEcZYIFd_n?usp=sharing)
  - [Medium](https://drive.google.com/drive/folders/1vhBinTDQmizwLFhyvJHmWZSEFkUs3yKh?usp=drive_link)
  - [High](https://drive.google.com/drive/folders/1_AeAvDs-WiUbtdMD26OeXlv2QUT7okab?usp=drive_link)

- **Artificial Noise Test Dataset (ANTD):**
  - [Low](https://drive.google.com/drive/folders/12oAfvrGaa1dz1UW7qFvEUrxEcZYIFd_n?usp=sharing)
  - [Medium](https://drive.google.com/drive/folders/1vhBinTDQmizwLFhyvJHmWZSEFkUs3yKh?usp=drive_link)
  - [High](https://drive.google.com/drive/folders/1_AeAvDs-WiUbtdMD26OeXlv2QUT7okab?usp=drive_link)

### **Augmented Complex Background Dataset (ACBD)**
[![Download ACBD](https://img.shields.io/badge/Download-Augmented%20Complex%20Background%20Dataset-blue?style=for-the-badge)](https://drive.google.com/file/d/1DUjHxkbySyzjjNEHgOaBgjHFhcz5cREP/view?usp=sharing)

---

## **Methodology**
This study evaluates the following models under various adverse conditions:
- **Models**: YOLOv5, YOLOv8, Faster-RCNN, RetinaNet, and YOLO-NAS
- **Evaluation Metrics**: Mean Average Precision (mAP) under adverse conditions such as rain, noise, and motion blur.
- The details methodology is explained in paper with DOI: https://www.mdpi.com/2504-446X/8/11/638.

---

## **Results**

<details>
<summary>Performance of ANTD</summary>
  
![ANTD](https://github.com/user-attachments/assets/66485f5d-ec7c-44d0-85d9-3ef3da788a5a)

<summary>Performance of MBTD </summary>

![MBTD](https://github.com/user-attachments/assets/ea0464b7-0d54-4c72-a417-325c9f0f11df)

<summary>Performance of RTD </summary>

![RTD](https://github.com/user-attachments/assets/90e972fb-9d61-46a6-ba5c-8b42b6933d54)


<summary>Overall Enhancement After Data Augmentation</summary>

![image](https://github.com/user-attachments/assets/13877e0f-5c93-4093-91b1-da14288d420f)

<summary>GRADCAM Results</summary>

![image](https://github.com/user-attachments/assets/760dd4df-80cc-4132-bbf9-861a1b5aa352)



</details>

---

