
# **RPN Fine-Tuning for People Detection**  
> **Using Penn-Fudan Dataset, PyTorch, and Real-Time Video Analysis**  

<div align="center">
  <img src="output_RPN.gif" alt="Object Detection" width="600" style="border-radius: 15px;" />
</div>

<p align="center">
  <em>Fine-tune a Region Proposal Network (RPN) to detect people in images and videos, in a single Jupyter Notebook!</em>
</p>

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/Framework-PyTorch-red)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)




## **Overview**

How to fine-tune a **Region Proposal Network (RPN)** for **person detection** using the **Penn-Fudan Pedestrian Detection** dataset. We leverage **PyTorch** and **torchvision** to achieve robust and efficient object detection, both for static images and real-time videos.



**Key points:**
- **End-to-End Pipeline**: From dataset preparation to inference on video streams.
- **Modular Code**: Easily swap backbones (e.g., ResNet, MobileNetV2).
- **Scalable**: Customize for more object categories or bigger datasets.
  
<div>
  <img src="https://miro.medium.com/v2/resize:fit:1200/1*ftTEVgsx0jfvUSFB6X5mQg.jpeg" alt="Model Architecture" width="600" style="border-radius: 15px;" />
</d >

---


## **Features**

1. **Comprehensive Notebook**  
   - Single Jupyter Notebook that demonstrates dataset loading, model training, evaluation, and inference.

2. **Real-Time Video Detection**  
   - Leverage OpenCV to process and annotate video frames in real time.

3. **Penn-Fudan Dataset**  
   - A small yet practical dataset for pedestrian detection tasks, perfect for learning and experimentation.

4. **Customizable Transforms**  
   - Plug-and-play transformations for data augmentation and preprocessing with random flips, resizing, and normalization.

5. **Instance Segmentation (Optional)**  
   - Option to use a Mask R-CNN architecture to generate segmentation masks.


<img src="https://h-huang.github.io/tutorials/_static/img/tv_tutorial/tv_image01.png" width="600" style="border-radius: 15px;" />

---

## **License**

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and distribute the code in your own projects.

---
