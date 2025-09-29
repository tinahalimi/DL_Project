# Object Detection and Multi-Object Tracking in Sports Videos

This repository contains the implementation of deep learning–based object detection and tracking algorithms applied to sports datasets. The project explores modern approaches for identifying and tracking multiple players and objects in dynamic environments such as football games.

---

## Project Overview

The project focuses on building a robust pipeline for real-time object detection and multi-object tracking (MOT) in sports analytics. Object detection was implemented using the **YOLO** family of models, while tracking was performed with both **DeepSORT** and **ByteTrack**. These methods were evaluated for their ability to maintain consistent player identities and adapt to challenges such as occlusions, fast motion, and camera shifts.

The main contributions of this project include:

- Implementation of **YOLO-based detection** models for player and object localization.  
- Integration of **DeepSORT** to leverage appearance embeddings for identity-preserving tracking.  
- Integration of **ByteTrack**, a recent lightweight tracking framework, to enhance efficiency and accuracy in high-motion environments.  
- Comparative analysis of DeepSORT and ByteTrack performance across sports datasets.  

---

## Repository Structure

- `DL_Project_Final.ipynb`: Main notebook containing detection and tracking experiments.  
- `Links.txt`: Reference links and supporting resources. 

---
