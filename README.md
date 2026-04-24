# Real-Time-Face Filter using OpenCV

A computer vision project that overlays sunglasses on a human face using OpenCV by applying image resizing, masking, and region-based blending techniques.

---

## Project Overview

The notebook performs the following steps:

- Load a face image  
- Load a PNG sunglass image with transparency (alpha channel)  
- Resize the sunglass to fit the face  
- Extract color and mask channels  
- Overlay the sunglass on the eye region  
- Display the final augmented image  

---

## Technologies Used

- OpenCV  
- NumPy  
- Matplotlib  
- Python  

---


---

## ⚙️ How It Works

### 1. Load Images
- Face image is loaded using OpenCV  
- Sunglass PNG is loaded with alpha channel  

### 2. Resize Sunglasses
- Adjust size to match eye region  

### 3. Extract Channels
- RGB channels → Sunglass image  
- Alpha channel → Mask  

### 4. Overlay Sunglasses
- Define Region of Interest (ROI)  
- Replace or blend the ROI with sunglass  

---

## 📸 Output Snippet

### Input

<img width="390" height="508" alt="my photo" src="https://github.com/user-attachments/assets/9492f173-755a-4786-b348-3392fe603b5b" />

<img width="627" height="273" alt="sunglass1" src="https://github.com/user-attachments/assets/54f3d463-92f1-4022-89c4-e7a46a9bfbd8" />

### Output
<img width="1374" height="857" alt="image" src="https://github.com/user-attachments/assets/35793606-6464-4f31-88ca-7c06cc7bc34b" />


---

## Key Learning Concepts

- Image reading and display using OpenCV  
- Understanding image dimensions and channels  
- Working with alpha channels (transparency)  
- Image masking and blending  
- Region of Interest (ROI) manipulation  

---

## Future Improvements

- Automatic face and eye detection using Haar Cascades  
- Dynamic positioning of sunglasses  
- Real-time webcam filter  
- Support for multiple accessories (hats, masks, etc.)  

---
