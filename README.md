# 🌿 Plant Leaf Disease Detection Incorporating IoT and XAI-Enhanced Deep Learning

[![Conference](https://img.shields.io/badge/ICCIT-2024-orange)](https://ieeexplore.ieee.org/abstract/document/11021966)

This repository contains the official implementation of our research **"Plant Leaf Disease Detection Incorporating IoT and XAI-Enhanced Deep Learning"**, accepted at the **2024 27th International Conference on Computer and Information Technology (ICCIT)**.

---

## 📄 Abstract

Plant diseases are a major threat to global agriculture, significantly affecting both food production and economic stability. Small-scale farmers often struggle with early disease recognition due to limited infrastructure and resources.

In this research, we propose a robust and cost-effective plant disease detection system that integrates:

- **Deep Learning (CNNs with InceptionNetV3, VGG16, EfficientNetB5)**
- **IoT (ESP32-CAM and Server-based Deployment)**
- **XAI (Explainable AI with Grad-CAM)**

Our system can predict **38 types of diseases across 14 plant species** even under low-resolution, noisy data. With the support of the ESP32-CAM module, our framework enables **real-time disease detection** and visualization of infected regions.

The proposed system achieved **~99% average accuracy** and provides an **affordable solution** for real-world agricultural use, especially in **resource-limited areas**.

---

## 🛠️ System Architecture

### 🔧 Proposed Framework

![Framework](Paper_images/framework.png)

### 💻 User Interface

![Interface](Paper_images/interface.png)

### 🧠 Grad-CAM Visualizations

![GradCAM](Paper_images/gradcam.png)

### 📊 Training Performance (Accuracy & Loss)

![Accuracy and Loss](Paper_images/Accuracy_Loss_CNN.png)

### 📡 IoT Circuit Design

![Circuit](Paper_images/CKT%20Graph_1.png)

### 🌱 Sample Plant Leaf Images

![Samples](Paper_images/sample.png)

---

## 🧪 Key Features

- 🔍 **High Accuracy**: ~99% classification performance across multiple deep models.
- 📷 **Low-Resolution Input Support**: Effective even with noisy, real-world data.
- 🌐 **IoT Integration**: ESP32-CAM for real-time deployment.
- 🧠 **Explainability**: Grad-CAM based infected area visualization.
- 💡 **Scalable & Affordable**: Designed for rural and low-resource regions.

## 🔗 Citation

If you use this work in your research, please cite it as:

````bibtex
@inproceedings{partho2024plant,
  title={Plant Leaf Disease Detection Incorporating IoT and XAI-Enhanced Deep Learning},
  author={Partho, Pijush Kanti Roy and Rafi, Md Abid Hasan and Bhowmik, Pankaj},
  booktitle={2024 27th International Conference on Computer and Information Technology (ICCIT)},
  pages={2552--2557},
  year={2024},
  organization={IEEE}
}

## 🚀 Get Started

To run this project locally:

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/PlantLeafDiseaseDetection.git
cd PlantLeafDiseaseDetection

### 2. Install the dependencies

```bash
pip install -r requirements.txt

### 3. Run the models using GPU.


## 👨‍💻 Authors

| Name                     | Email                          | GitHub                                        |
|--------------------------|--------------------------------|-----------------------------------------------|
| Pijush Kanti Roy Partho | pijushkantiroy2040@gmail.com | [@InquietoPartho](https://github.com/InquietoPartho) |
| Md Abid Hasan Rafi      | ahr16.abidhasanrafi@gmail.com     | [@AbidHasanRafi](https://github.com/AbidHasanRafi)     |
| Pankaj Bhowmik          | pankaj.cshstu@gmail.com           | [@pjbk](https://github.com/pjbk) |
````

## 📣 Acknowledgments

We would like to express our sincere gratitude to **Pankaj Bhowmik Sir** for his invaluable guidance, supervision, and continuous support throughout this research work. His mentorship was pivotal in shaping the direction and quality of this project.

---

## 📬 Contact

For any inquiries, collaborations, or feedback, feel free to reach out:

- **Pijush Kanti Roy Partho**  
  📧 pijushkantiroy2040@gmail.com  
  🔗 [GitHub: @InquietoPartho](https://github.com/InquietoPartho)
