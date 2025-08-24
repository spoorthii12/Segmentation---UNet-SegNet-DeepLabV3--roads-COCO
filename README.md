# **Semantic Segmentation on Roads & COCO Dataset**

*Using UNet, SegNet, and DeepLabV3 Architectures*

## **📌 Overview**

This repository contains implementations of **semantic segmentation** models — **UNet**, **SegNet**, and **DeepLabV3** — trained and evaluated on two datasets:

* **Roads dataset** — for road segmentation tasks.
* **COCO dataset** — for multi-class segmentation.

The project compares the performance of these architectures on both datasets to understand their strengths, weaknesses, and real-world applicability.

---

## **🧠 Architectures Implemented**

* **UNet** → Best for medical & small-scale segmentation tasks due to skip connections.
* **SegNet** → Lightweight encoder-decoder-based architecture with better efficiency.
* **DeepLabV3** → State-of-the-art architecture using **Atrous Convolutions** & **Spatial Pyramid Pooling** for multi-scale context.

---

## **📂 Dataset Details**

### **1. Roads Dataset**

* **Description** → Pixel-wise road segmentation for autonomous driving tasks.
* **Link** → [Roads Dataset](https://app.segments.ai/artificialbeans/road/samples)

### **2. COCO Dataset**

* **Description** → A large-scale object detection, segmentation, and captioning dataset.
* **Link** → [COCO Dataset](https://cocodataset.org/#download)

## **⚙️ Installation**

```bash
# Clone the repository
git clone https://github.com/spoorthii12/Segmentation---UNet-SegNet-DeepLabV3--roads-COCO.git

# Navigate to project directory
cd Segmentation---UNet-SegNet-DeepLabV3--roads-COCO

# Install dependencies
pip install -r requirements.txt
```

---

## **🚀 Training & Evaluation**

### **1. For Roads Dataset**

```bash
# UNet
Open UNet_roads.ipynb and run all cells

# SegNet
Open SegNet_roads.ipynb and run all cells

# DeepLabV3
Open DeepLabV3-roads.ipynb and run all cells
```

### **2. For COCO Dataset**

```bash
# UNet
Open UNet_COCO.ipynb and run all cells

# DeepLabV3
Open DeepLabV3COCO.ipynb and run all cells
```
---

## **🔮 Future Improvements**

* Add **DeepLabV3+** for better boundary refinement
* Integrate **transformer-based segmentation models** (e.g., SegFormer, Mask2Former)
* Hyperparameter tuning for better COCO results
* Deploy trained models using **Streamlit** or **Gradio**

