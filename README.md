## YOLOv9  VS  FASTER-RCNN

# Objective
The objective of the project is to evaluate and compare the performance of two state-of-the-art object detection algorithms, Faster R-CNN and YOLO (You Only Look Once), specifically in the context of personal protective equipment (PPE) detection. The project aims to analyze and compare the speed, accuracy, and efficiency of both algorithms when detecting various types of PPE items, such as helmets, safety vests, goggles, and gloves, within a given dataset. By conducting this comparative analysis, the project seeks to provide insights into which algorithm may be more suitable for real-world applications requiring rapid and accurate detection of PPE items.

# Tools
![image](https://github.com/Anjali162004/CV-Project/assets/111984924/6d4cfeda-7a06-45c5-b62f-942148ec3bec)

# Models
The initial step involved finding the most recent studies addressing the PPE Detection problem. I sought to understand common approaches and models. Three notable studies were identified:

PPE detector: a YOLO-based architecture to detect personal protective equipment (PPE) for construction sites (2022)

Personal Protective Equipment Detection: A Deep-Learning-Based Sustainable Approach (2023)

Artificial Intelligence System for Detecting the Use of Personal Protective Equipment (2023)

All three studies predominantly featured the YOLOv5 model. Study 2, which listed various studies and ranked models, reported that Faster R-CNN with a ResNet50 backbone exhibited a superior mAP50 (96%) compared to YOLOv5 (63%) when trained to 20 epochs. Given the disparate datasets and classes used, I decided to explore and compare Faster R-CNN with the most recent YOLOv9 models.

# DATA
The dataset consists of images collected from construction sites with annotations for detecting various types of personal protective equipment (PPE), including hard hats, safety vests, and goggles. Each image is annotated with bounding boxes indicating the location of different PPE items. 

The Dataset containes 10 classes.
train set size: 2605
valid set size: 114
test set size: 82


![image](https://github.com/Anjali162004/CV-Project/assets/111984924/99269daa-6488-4442-b040-634d3b546b68)

## Results
# YOLOv9

![image](https://github.com/Anjali162004/CV-Project/assets/111984924/5e0135fd-8a94-4ef7-93bc-5f43f95aa7b0)

 ![image](https://github.com/Anjali162004/CV-Project/assets/111984924/c5cfc07c-a7c0-4b94-8705-708c65f3170f)

 ![image](https://github.com/Anjali162004/CV-Project/assets/111984924/f5e84a63-c6c9-4077-8937-332dd55de93c)

 ![image](https://github.com/Anjali162004/CV-Project/assets/111984924/626a91cb-2614-45ea-a0b0-ce75bcacaff5)

 ![image](https://github.com/Anjali162004/CV-Project/assets/111984924/92b95c50-4968-4d7e-8d1c-96ee4049bbd3)

 # Faster-RCNN

 ![image](https://github.com/Anjali162004/CV-Project/assets/111984924/3fe512b6-fee1-430e-802d-3bfc76b41153)

![WhatsApp Image 2024-04-11 at 11 17 19_dd56f73b](https://github.com/Anjali162004/CV-Project/assets/111984924/24ad5d1f-2933-48bc-8212-96bcd29e5b9f)

![WhatsApp Image 2024-04-11 at 11 16 45_2de490b2](https://github.com/Anjali162004/CV-Project/assets/111984924/06dc81fe-426a-4981-9692-e82506c364f7)

![image](https://github.com/Anjali162004/CV-Project/assets/111984924/c09cd9cd-12e9-4170-9337-d11265bab1b9)

![image](https://github.com/Anjali162004/CV-Project/assets/111984924/f8770e1e-e819-44df-aeff-64f9bf182974)
















