# 🌊 Deep-Sea Marine Debris Detection with YOLOv11x

## 📽️ Detection Demo
 
https://github.com/user-attachments/assets/8640b47c-5bf7-4b52-8e2d-3285f992cdbe

## 📘 Introduction

Marine debris in deep-sea environments poses significant threats to marine ecosystems due to its persistence and inaccessibility. While surface-level and coastal pollution mitigation efforts have progressed, the complexity of underwater environments has limited advancements in detecting and removing deep-sea debris effectively.

Autonomous Underwater Vehicles (AUVs) offer a promising solution for exploring and cleaning deep-sea environments. However, their success depends on the development of efficient detection systems. Traditional methods, often manual and resource-intensive, are inadequate for the vast and remote ocean floor. This project leverages deep learning to create a robust detection and classification system tailored for these challenging conditions.

## 🎯 Motivation

Marine debris accumulation on the ocean floor disrupts ecosystems and harms marine life. The long-term presence of pollutants impacts biodiversity, food chains, and habitats. While surface-level debris management has improved, the detection and removal of deep-sea debris remain limited by traditional approaches' inefficiencies.

Advances in AUV technology have opened possibilities for automated deep-sea exploration, but their potential is constrained by a lack of reliable detection methods. By harnessing the capabilities of deep learning, this research aims to automate and enhance debris detection in challenging underwater environments, enabling effective AUV-based cleanup operations.

## 🔍 Problem Statement

The lack of efficient and accurate methods for detecting deep-sea debris restricts efforts to clean the ocean floor and mitigate ecological harm. Autonomous Underwater Vehicles (AUVs) require scalable and reliable detection systems to improve cleanup operations in these environments.

This project addresses these challenges by:

- Constructing a comprehensive 3D dataset for diverse debris types in underwater environments.
- Developing YOLOv11x, a deep learning-based detection model optimized for accuracy and speed.
- Benchmarking the model against existing techniques to establish its performance and reliability.

Expected contributions include a valuable dataset for future research, a high-performing detection network, and actionable insights into the challenges and solutions for deep-sea debris management.

## 🧠 Technical Overview

### 📦 Dataset

- **Source**: Derived from JAMSTEC's database and additional sources from the Indian Ocean.
- **Composition**: 3D deep-sea images annotated across 15 marine debris categories.
- **Format**: Structured for object detection tasks.

### 🧰 Model Architecture

- **Backbone**: YOLOv11x for real-time object detection.
- **Optimization**: Model pruning and OpenCV enhancements to reduce processing latency by 40%, facilitating deployment on AUVs and UAVs.

### 📊 Performance

- **Accuracy**: Achieved 89% accuracy in classifying marine debris.
- **mAP@0.5**: Improved from 0.20 to 0.80.
- **Latency**: Reduced by 40% through optimization techniques.



<!--
<video width="600" controls>
  <source src="[https://user-images.githubusercontent.com/USER_ID/FILE_NAME.mp4](https://github.com/user-attachments/assets/783816d8-a58a-47ed-9bc0-96c5d899096a)" type="video/mp4">
  Your browser does not support the video tag.
</video>

-->


## 🛠️ Languages & Tools

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="PyTorch" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg" alt="OpenCV" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="40" height="40"/>
</p>

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- PyTorch
- OpenCV

