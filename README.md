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

## How It Works

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

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/9492f173-755a-4786-b348-3392fe603b5b" width="300"/><br>
      <b>Face Image</b>
    </td>
    <td align="center">
      <img width="300"src="https://github.com/user-attachments/assets/2b83d4f1-3e68-482f-bceb-cc3a05e5cb23" />
<br>
      <b>Sunglass Image</b>
    </td>
  </tr>
</table>

### Output

<p align="left">
  <img src="https://github.com/user-attachments/assets/8d2f7a22-a8b2-4e56-a196-68337bcd6243" width="600"/>
</p>



## Future Improvements

- Automatic face and eye detection using Haar Cascades  
- Dynamic positioning of sunglasses  
- Real-time webcam filter  
- Support for multiple accessories (hats, masks, etc.)  

---

## Result

The project successfully overlays a sunglass image onto a human face using image processing techniques such as resizing, masking, and region-based blending.
