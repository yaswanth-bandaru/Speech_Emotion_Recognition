# Speech_Emotion_Recognition

# Approach

* Read WAV files in by using the libROSA package in Python.
* Extract features from the audio files using libROSA. 
* Fit various Machine Learning and Deep Learning models.
* Ensemble models using soft voting classifier to improve performance.
* Use VGG 16 model on images of spectrograms.
* Ensemble the CNN with the VGG 16 to improve performance.

# Results

VGG16 with CNN performed best with an accuracy of 75%.

## Classification Report

![Capture](https://user-images.githubusercontent.com/30667531/115498237-d88b3b80-a232-11eb-8496-db58c7ee0c3e.PNG)

## Confusion Matrix

![Capture1](https://user-images.githubusercontent.com/30667531/115498250-e0e37680-a232-11eb-938e-93142d01ec0d.PNG)

