# BRAIN TUMOUR SEGMENTATION USING COMPUTER VISION 
 
## Problem Statement 
---
Brain tumors are one of the most life-threatening diseases worldwide, and early 
diagnosis plays a crucial role in successful treatment. Manual diagnosis of MRI scans is time
consuming, subjective, and error-prone, often requiring expert radiologists. There is a need 
for an automated, accurate, and efficient solution to detect and segment brain tumors in MRI 
images using computer vision and deep learning techniques.
---
###Scope of the Project 
---
 The system will classify MRI images into two classes: Tumor and No Tumor. 
 It focuses on binary classification, not segmentation of tumor size or type. 
 Works with 2D image slices (RGB format) resized to fixed dimensions. 
 Can be extended to multi-class classification or full segmentation using 3D models in 
future. 
---
###Tools and Technologies Used 
---
#####Category Tools/Technologies 
---
Programming Python 
Libraries OpenCV, NumPy, PIL, Matplotlib, scikit-learn 
Deep Learning Keras (with TensorFlow backend) 
Model Type Convolutional Neural Network (CNN) 
Data Handling Train-test split using sklearn 
Visualization Matplotlib 
Deployment (optional) Streamlit / Flask 
---
###Modules of the Project 
---
1. Data Collection 
o Labeled brain MRI images (yes for tumor, no for no tumor). 
2. Data Preprocessing 
o Image resizing, normalization, noise removal. 
3. Model Building (CNN) 
o Layers: Convolution → ReLU → MaxPooling → Dense → Dropout. 
4. Model Training & Evaluation 
o Binary classification using sigmoid activation. 
o Metrics: Accuracy, loss, and visual inspection. 
5. Model Saving

##Future Enhancements 
---
 Use 3D U-Net for tumor segmentation rather than classification. 
 Incorporate transfer learning with pre-trained models like VGG16 or ResNet. 
 Create a web-based diagnostic tool for real-time predictions. 
 Extend to multi-class classification (glioma, meningioma, pituitary). 
