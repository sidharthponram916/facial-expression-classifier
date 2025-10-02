# Facial Expression Recognition (FER2013)

A deep learning project that detects human emotions from facial images using the **FER2013 dataset**.  
Each image (48×48 grayscale) is classified into one of seven emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, or Neutral.

## Project Premise
Using a CNN built with **TensorFlow/Keras**, the model learns emotion patterns from thousands of labeled faces — predicting how someone feels from a single photo.

## Technologies Used
- **Python**, **TensorFlow/Keras**, **NumPy**, **Pandas**, **Matplotlib**, **scikit-learn**
- Trained on **Google Colab** with GPU support  
- Model includes multiple **Conv2D**, **BatchNorm**, **Dropout**, and **Dense** layers  
- Saved best model checkpoints for accuracy tracking  


## Summary
The model successfully classifies facial expressions with ~70% accuracy and visualizes results dynamically during prediction. Future improvements includes optimizing the model to increase accuracy to around 80-90% as well as integrating the model into a web app. 
