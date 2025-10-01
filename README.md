# MEIWVD
MEIWVD: Multi-Environment Inland Waterway Vessel Detection Dataset
1. Overview

The MEIWVD (Multi-Environment Inland Waterway Vessel Detection) dataset is designed to advance research in water surface object detection, specifically targeting common surface objects in inland waterways of the Yangtze River basin. The dataset spans six months (November 2023 to April 2024) and includes video clips capturing diverse perspectives, lighting conditions, weather scenarios, and complex navigational environments. Due to restrictions imposed by maritime regulatory authorities, only a subset of the data and annotations is publicly available.
This repository provides access to the MEIWVD dataset and related resources to support researchers in developing robust object detection models for inland waterway applications. The dataset is published in conjunction with the paper "Inland Waterway Object Detection in Multi-environment: Dataset and Approach", which is forthcoming in Engineering Applications of Artificial Intelligence.

2. Dataset Description

The MEIWVD dataset was constructed using Hikvision cameras installed along the riverbanks of the Yangtze River, with careful adjustments to ensure comprehensive coverage of water surface areas. The dataset includes 119 preprocessed video clips rich in surface objects, meticulously annotated using the DarkLabel tool. The data captures the following key features:

(1) Multi-perspective: Objects are captured from multiple angles (front, rear, side) to enhance detection robustness across viewpoints.

(2) Multi-light: Images cover varied lighting conditions, including strong sunlight, low light, and artificial lighting.

(3) Multi-weather: Data includes diverse meteorological conditions such as sunny, cloudy, rainy, and foggy weather.

(4) Multi-scenario: The dataset accounts for occlusions (e.g., partial vessel obstruction) and complex backgrounds (e.g., urban or natural river settings).

3.Data Collection and Preprocessing

Data collection occurred over six months (November 2023 to April 2024). Preprocessing involved:

(1) Elimination of unrecognizable images: Images with severely compromised visibility (e.g., due to heavy rain or dense fog) were excluded.

(2) Multi-environment focus: Special weather and lighting conditions were prioritized to simulate real-world inland waterway challenges. Some difficult-to-recognize images were included with accurate annotations based on contextual information to enhance detector training.

4. Dataset Access
   
The MEIWVD dataset is publicly available for download at:https://pan.baidu.com/s/1qG963NYsQdqeKR47fcpqTg?pwd=xjvx

Note: Due to maritime regulatory constraints, only a subset of the data and annotations is publicly available. Researchers are encouraged to use this resource to advance studies in water surface object detection.

5. Citation
   
Please cite our paper if you use this dataset in your research:
Shanshan Wang, Haixiang Xu, Hui Feng, et al. Inland Waterway Object Detection in Multi-environment: Dataset and Approach, Engineering Applications of Artificial Intelligence, 2025.[Link to paper (to be updated upon publication)]

6. Usage
   
The dataset is intended for research purposes, particularly for developing and evaluating object detection models in complex inland waterway environments. 
