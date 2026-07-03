# 🖼️ COCO Dataset Exploration and Analysis

## 📌 Project Overview

This project explores and analyzes the **COCO (Common Objects in Context) 2017 Validation Dataset** to understand its structure and characteristics for computer vision and text-to-image applications.

The project includes loading the dataset, analyzing object classes, studying caption lengths, examining image resolutions, and visualizing images together with their text descriptions.

---

## 📂 Dataset Used

**Dataset:** COCO 2017 Validation Dataset

Dataset Statistics:

* Total Images: **5,000**
* Total Object Classes: **80**
* Total Captions: **25,000**
* Captions per Image: **5**

The COCO dataset is widely used for object detection, image captioning, and text-to-image generation research.

---

## 🎯 Objectives

* Load and examine a public dataset
* Analyze the number of object classes
* Study caption (description) lengths
* Analyze image resolutions
* Display images with their corresponding text descriptions
* Visualize important dataset statistics

---

## 🔍 Analysis Performed

### 1. Dataset Loading

* Installed and used `pycocotools`
* Downloaded COCO annotations and validation images
* Loaded caption and instance metadata

### 2. Class Analysis

* Identified all 80 object categories
* Displayed category names and total class count

### 3. Caption Analysis

* Calculated:

  * Total captions
  * Average caption length
  * Minimum caption length
  * Maximum caption length
* Visualized caption-length distribution using a histogram

### 4. Image Resolution Analysis

* Computed average image width and height
* Explored resolution diversity across the dataset
* Visualized image dimensions using a scatter plot

### 5. Image and Text Exploration

* Displayed sample images together with their captions
* Verified the relationship between visual content and textual descriptions

---

## 📸 Project Outputs

### Sample Image with Captions

![Sample Image](outputs/sample_image_with_captions.png)

### Caption Length Distribution

![Caption Length Distribution](outputs/caption_length_distribution.png)

### Image Resolution Distribution

![Image Resolution Distribution](outputs/image_resolution_distribution.png)

---

## 🛠️ Technologies Used

* Python
* Google Colab
* NumPy
* Matplotlib
* Pillow (PIL)
* pycocotools

---

## 📦 Requirements

```bash
pip install -r requirements.txt
```

---

## ✅ Task Completion

This project successfully satisfies the following requirements:

* ✔ Load and examine a public dataset (COCO)
* ✔ Analyze the number of classes
* ✔ Analyze description lengths
* ✔ Analyze image resolutions
* ✔ Display text descriptions together with images
* ✔ Visualize dataset statistics using graphs
