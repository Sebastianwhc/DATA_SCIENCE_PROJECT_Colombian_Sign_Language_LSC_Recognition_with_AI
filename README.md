Of course! Here is the README.md file, translated into English.

🤖 Colombian Sign Language (LSC) Recognition with AI
This project is a real-time prototype for recognizing static letters of the Colombian Sign Language (LSC) alphabet using a webcam.

It uses MediaPipe for hand landmark detection and extraction, and a Sequential Neural Network (MLP) built with TensorFlow/Keras to classify the corresponding sign.

🚀 Features
Feature Extraction: Uses MediaPipe Hands to extract 63 coordinates (21 points in x, y, z) from the hand.

AI Model: A simple sequential neural network trained to classify these coordinates.

Real-Time Detection: Opens the webcam, detects the hand, and displays the predicted letter and confidence level on-screen.

💻 Technologies Used
Python 3.12

TensorFlow / Keras: For building and training the neural network.

MediaPipe: For hand detection and landmark extraction.

OpenCV: For webcam video capture and processing.

Scikit-learn: For data preprocessing (LabelEncoder, train_test_split).

Pandas: For manipulating and saving the processed data.

Jupyter Notebook: As the development and experimentation environment.
