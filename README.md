# Face-mask-detection


**This project aims to detect human faces with and without masks in real-time using a machine learning model that leverages transfer learning. The model is trained to detect face mask presence and can be used to prevent COVID-19 virus spreading.**
Features
Detects human faces with and without masks in real-time using a webcam feed.
Uses Keras for developing the model and Resnet-50 for training.
Performs data augmentation (horizontal and vertical shift, flip) as a preprocessing step.
Achieves 99% accuracy while testing with hold-out images.
Uses OpenCV to detect face masks in real-time.
Getting Started
Clone the repository:
git clone https://github.com/Aniketh999/Face-mask-detection.git

Install the required libraries:
pip install -r requirements.txt

Run the maskDetection.ipynb file to train the model and test its performance.
To run the face mask detection application, ensure a webcam is plugged in and run the MaskOrNot.py file.
Model Training Data
The training data for this model can be found in the following link:
Face Mask Detection Training Data
Code and Performance
For the code and performance, check the maskDetection.ipynb file.
