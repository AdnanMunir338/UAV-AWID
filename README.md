**Impact of Adverse Weather and Image Distortions on Vision-Based UAV Detection: A Performance Evaluation of Deep Learning Models**

**Abstract**

Unmanned aerial vehicle (UAV) detection in real-time is a challenging task despite the advances in computer vision and deep learning techniques. The increasing use of UAVs in numerous applications 
has generated worries about possible risks and misuse. Although vision-based UAV detection methods have been proposed in recent years, a standing open challenge and overlooked issue is that of adverse weather.
This work is the first, to the best of our knowledge, to investigate the impact of adverse weather conditions and image distortions on vision-based UAV detection methods. To achieve this, a custom training 
dataset was curated with images containing a variety of UAVs in diverse complex backgrounds. In addition, this work develops a first-of-its-kind dataset, to the best of our knowledge, with UAV-containing images affected by adverse conditions. Based on the proposed datasets, a comprehensive benchmarking study is conducted to evaluate the impact of adverse weather and image distortions on the performance of popular object detection methods such as YOLOv5, YOLOv8, Faster-RCNN, RetinaNet, and YOLO-NAS. The experimental results reveal the weaknesses of the studied models and the performance degradation due to adverse weather, 
highlighting avenues for future improvement. The results show that even the best UAV detection model’s performance degrades in mean average precision (mAP) by −50.62 points in torrential rain conditions, 
by −52.40 points in high noise conditions, and by −77.0 points in high motion blur conditions. To increase the selected models’ resilience, we propose and evaluate a strategy to enhance the training of the 
selected models by introducing weather effects in the training images. For example, the YOLOv5 model with the proposed enhancement strategy gained +35.4, +39.3, and +44.9 points higher mAP in severe rain, noise, 
and motion blur conditions respectively. The findings presented in this work highlight the advantages of considering adverse weather conditions during model training and underscore the significance of data 
enrichment for improving model generalization. The work also accentuates the need for further research into advanced techniques and architectures to ensure more reliable UAV detection under extreme weather 
conditions and image distortions.


The **complex background dataset (CBD)** can be downloaded from this link 

https://drive.google.com/file/d/1-BmnQe9LllS7EA4NhGGj-2f7MKZjfnR-/view?usp=sharing

**The UAV-AWID (UAVs-Adv Weather and Image Distortions)**

The Rainy test DataSet (RTSD):

Drizzle: https://drive.google.com/drive/folders/1tZY-CggDojx5xMS9icmvwH1qBpioTFKt?usp=drive_link

Heavy: https://drive.google.com/drive/folders/1vhBinTDQmizwLFhyvJHmWZSEFkUs3yKh?usp=drive_link

Torrential: https://drive.google.com/drive/folders/1_AeAvDs-WiUbtdMD26OeXlv2QUT7okab?usp=drive_link

The Motion Blur Test DataSet (MBTD):

Low: https://drive.google.com/drive/folders/12oAfvrGaa1dz1UW7qFvEUrxEcZYIFd_n?usp=sharing

Medium: https://drive.google.com/drive/folders/1vhBinTDQmizwLFhyvJHmWZSEFkUs3yKh?usp=drive_link

High: https://drive.google.com/drive/folders/1_AeAvDs-WiUbtdMD26OeXlv2QUT7okab?usp=drive_link

The Artificial Noise Test DataSet (ANTD):

Low: https://drive.google.com/drive/folders/12oAfvrGaa1dz1UW7qFvEUrxEcZYIFd_n?usp=sharing

Medium: https://drive.google.com/drive/folders/1vhBinTDQmizwLFhyvJHmWZSEFkUs3yKh?usp=drive_link

High: https://drive.google.com/drive/folders/1_AeAvDs-WiUbtdMD26OeXlv2QUT7okab?usp=drive_link

**Augmented Complex Background Dataset (ACBD)**:

https://drive.google.com/file/d/1DUjHxkbySyzjjNEHgOaBgjHFhcz5cREP/view?usp=sharing

Download the Yolov5 train model weights from given link:

https://drive.google.com/file/d/1yp2DUWOnLJI5-lnd0n15x-fxVUK9qZOc/view?usp=sharing

Download the Yolov8 train model weights from given link:

https://drive.google.com/file/d/1dIdblRKixr_9cDYnYQY6iMTxAxDj5DKo/view?usp=sharing

Download the Faster_RCNN train model weights from given link:

https://drive.google.com/file/d/10GjZxSBuyVJ_puINCJNFPxGmmLGnOnok/view?usp=sharing

Download the Retina_Net train model weights from given link:

https://drive.google.com/file/d/1d9DjLROo1zhCo48DBgH1i81JaqnF8MAM/view?usp=sharing

Download the Yolo_Nas train model weights from given link:

https://drive.google.com/file/d/19ZlJcRUQ3mWyfPwRx2fcjC6bKPVXHU_2/view?usp=sharing

Video for Enhanced YOLOv5 Model:

https://drive.google.com/file/d/1H531EM6LKWs3Cos3MSmcPnUByS7inhCp/view?usp=drive_link








