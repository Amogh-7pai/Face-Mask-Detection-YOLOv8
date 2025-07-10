# 😷 Face Mask Detection using YOLOv8

This project uses **YOLOv8** for face mask detection, classifying faces into:
- ✅ With Mask
- ❌ Without Mask
- ⚠️ Mask Worn Incorrectly

---

## 📋 Project Overview

This project demonstrates how to:
1. **Preprocess & Convert a Face Mask Dataset** to YOLOv8 format.
2. Train the YOLOv8 model for **face mask detection**.
3. Evaluate the trained model and visualize the results inside the notebook.
4. Predict face mask usage in new images.

It is built for easy use in **Google Colab** and can be extended further.

---

## 🚀 Features
- Fully automated dataset conversion and YOLOv8 training pipeline.
- Detects multiple faces with or without masks in the same image.
- Visual output shown directly in the notebook.
- Customizable for other datasets too.

---

## 📂 Project Structure
/datasets/ → YOLO-ready dataset (images & labels)
/face_mask/ → Original dataset (images & annotations)
/runs/ → Training results and model weights
Mask_project.ipynb → Main notebook (Colab Ready)

---

## ✅ Sample Output
Includes prediction results shown inside the notebook for easy evaluation.

---

## ⚠️ Note
This project is designed for **Google Colab** (GPU Recommended).  
Training locally may be very slow without GPU.

---

## 📥 Dataset Access
The dataset (`face_mask.zip`) used in this project is not included in this repository due to file size limits.

➡️ To run this project:
1. Download the dataset manually from your local storage.
2. Upload it inside the Colab notebook when prompted (automated in the notebook).
3. Link to the datset:https://www.kaggle.com/datasets/andrewmvd/face-mask-detection

---

## 📋 Requirements
- Python  
- Ultralytics (YOLOv8)  
- OpenCV  
- Matplotlib  

---

## 💻 Steps to Run
### Step 1: Dataset Preprocessing  
- Upload & unzip the dataset ZIP file.
- Convert annotations (XML) to YOLO format.

### Step 2: Train YOLOv8 Model  
- Install Ultralytics and train YOLOv8 on the dataset.

### Step 3: Evaluate the Model  
- Check loss curves, metrics like mAP, and visualize training progress.

### Step 4: Predict New Images  
- Upload an image and see the predicted bounding boxes & classes.

---

## 📊 Model Info:
- Model: YOLOv8  
- Trained on: Custom Face Mask Dataset  
- Output: Bounding boxes with labels (Mask / No Mask / Mask Worn Incorrectly)
- 
- This model currently detects:
- ✅ With Mask
- ❌ Without Mask

**Note:** Though the dataset has 3 classes, the current trained model reliably detects only 2 classes due to dataset imbalance and limited training time.
