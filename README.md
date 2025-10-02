# Facial Expression Recognition (FER2013)

A deep learning project that detects human emotions from facial images using the **FER2013 dataset**.  
Each image (48×48 grayscale) is classified into one of seven emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, or Neutral.

---

## Project Premise
The goal was to teach a computer how to “read” facial expressions.  
Using a CNN built with **TensorFlow/Keras**, the model learns emotion patterns from thousands of labeled faces — predicting how someone feels from a single photo.

---

## Technologies Used
- **Python**, **TensorFlow/Keras**, **NumPy**, **Pandas**, **Matplotlib**, **scikit-learn**
- Trained on **Google Colab** with GPU support  
- Model includes multiple **Conv2D**, **BatchNorm**, **Dropout**, and **Dense** layers  
- Saved best model checkpoints for accuracy tracking  

---

## Summary
The model successfully classifies facial expressions with solid accuracy and visualizes results dynamically during prediction.  
Future improvements include adding data augmentation and deploying it as a live emotion recognition app.
