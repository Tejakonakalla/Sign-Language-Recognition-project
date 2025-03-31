# Sign Language Recognition ✋🧠

This project implements a real-time Sign Language Recognition system using computer vision and deep learning. It recognizes American Sign Language (A-Y, excluding J) and converts gestures into text.

## 🚀 About This Project

- ✅ Developed using Python, OpenCV, Keras, and CNN models.
- 📷 Captures hand gestures from the webcam.
- 🧠 Trained a Convolutional Neural Network (CNN) for alphabet classification.
- 🔤 Displays real-time predictions of sign language gestures.

## 📂 Project Structure

- `Gesture_Recognize_sign.py`: Main script to run the recognizer.
- `Image_capturing.py`: Script to collect training data using a webcam.
- `Image_preprocessing.py`: Processes collected images for model training.
- `model.ipynb`: Contains the model building and training code.
- `new_model6.h5`: Trained CNN model file.
- `sample.jpg` & `Demo.gif`: Sample image and demo visualization.

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Tejakonakalla/Sign-Language-Recognition-project.git
   cd Sign-Language-Recognition-project
💡 Personal Note

This project was explored to understand how computer vision and deep learning can help in real-time communication challenges—specifically for individuals who rely on sign language. I was curious to learn how CNNs perform on gesture-based data and how OpenCV helps in preprocessing. The journey involved working with image data, training models, and integrating everything into a functional recognizer. I also overcame Git and environment setup issues to confidently manage and deploy my code.

I plan to expand this project by:

Adding support for more characters and gestures.

Improving the model’s accuracy.

Making a user-friendly UI for practical usage.
