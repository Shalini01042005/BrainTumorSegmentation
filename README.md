# BRAIN TUMOUR SEGMENTATION USING COMPUTER VISION 
 
## Problem Statement 

Brain tumors are one of the most life-threatening diseases worldwide, and early 
diagnosis plays a crucial role in successful treatment. Manual diagnosis of MRI scans is time
consuming, subjective, and error-prone, often requiring expert radiologists. There is a need 
for an automated, accurate, and efficient solution to detect and segment brain tumors in MRI 
images using computer vision and deep learning techniques.

### Scope of the Project 

1. The system will classify MRI images into two classes: Tumor and No Tumor. 
2. It focuses on binary classification, not segmentation of tumor size or type. 
3. Works with 2D image slices (RGB format) resized to fixed dimensions. 
4. Can be extended to multi-class classification or full segmentation using 3D models in 
future. 
---
### Tools and Technologies Used 
### Category Tools/Technologies 

1. Programming Python 
2. Libraries OpenCV, NumPy, PIL, Matplotlib, scikit-learn 
3. Deep Learning Keras (with TensorFlow backend) 
4. Model Type Convolutional Neural Network (CNN) 
5. Data Handling Train-test split using sklearn 
6. Visualization Matplotlib 
7. Deployment (optional) Streamlit / Flask 
---
### Modules of the Project 

1. Data Collection : Labeled brain MRI images (yes for tumor, no for no tumor). 
2. Data Preprocessing : Image resizing, normalization, noise removal. 
3. Model Building (CNN) Layers: Convolution → ReLU → MaxPooling → Dense → Dropout. 
4. Model Training & Evaluation : Binary classification using sigmoid activation. 
---
### Future Enhancements 

1. Use 3D U-Net for tumor segmentation rather than classification. 
2. Incorporate transfer learning with pre-trained models like VGG16 or ResNet. 
3. Create a web-based diagnostic tool for real-time predictions. 
4. Extend to multi-class classification (glioma, meningioma, pituitary).
---
