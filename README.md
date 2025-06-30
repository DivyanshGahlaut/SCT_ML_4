# HandGesture-Recognition-CNN  

"company": SkillCraft Technology

"NAME":DIVYANSH GAHLAUT

"INTERN ID" :SCT/JUN25/6158

"DOMAIN" : Machine Learning

"DURATION": 4 WEEKS

*Project Description:

This project focuses on building a Convolutional Neural Network (CNN) based deep learning model to recognize and classify hand gestures from static images. The primary goal is to enable real-time or batch gesture classification that can be integrated into gesture-based control systems, sign language interpretation, or human-computer interaction interfaces.

The model is trained on the LeapGestRecog Dataset from Kaggle, which contains thousands of grayscale gesture images captured using a Leap Motion sensor. These images represent different static hand gestures, categorized into folders named 00 to 09.

🛠️ Tools & Technologies Used:

 Category               Tools / Frameworks                                                                       

*Language**             Python                                                                                   
*Libraries**            NumPy, OpenCV, TensorFlow, Keras                                                        
*IDE**                  VS Code                                                                                  
*Dataset Source**       [LeapGestRecog Dataset on Kaggle](https://www.kaggle.com/datasets/gti-upm/leapgestrecog) 
*Model Architecture**   Convolutional Neural Network (CNN)                                                       
*Image Preprocessing**  Resizing, Normalization (0-1), Grayscale   

⚙️ How It Works:

1.Data Collection & Preparation:

Dataset downloaded from Kaggle.

The dataset contains 10 gesture classes (00 to 09) with each class having images stored in individual folders.

Data is split into training and testing folders (train/, test/) or restructured using a Python script if needed.

2.Data Preprocessing:

All images are resized to 64x64 pixels.

Pixel values are normalized (divided by 255) to improve model convergence.

Image data is reshaped for model input as (batch, height, width, channels).

3.Model Architecture (CNN):

Several convolutional and pooling layers.

Flatten layer followed by dense layers.

Final softmax output layer for classification of 10 gesture classes.

5.Training:

Model is compiled using categorical_crossentropy and adam optimizer.

Trained for a number of epochs on the preprocessed training dataset.

6.Prediction:

A predict.py script is used to load the trained model and predict the gesture class of a test image.

Uses OpenCV to read and preprocess the image before feeding it into the model.

#Dataset Link:
 
LeapGestRecog Dataset
https://www.kaggle.com/datasets/gti-upm/leapgestrecog

#OUTPUT:

![Image](https://github.com/user-attachments/assets/c102cf60-1cc3-49d4-8c97-a2f2a52fc708)
