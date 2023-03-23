# ID-classifier
This project aims to classify ID cards into different categories based on the type of card, such as driver's license, passport, student ID, etc. The project is designed to run on the NVIDIA Jetson Kit, which provides high-performance computing capabilities, making it suitable for real-time image processing.

**Getting Started**:

**Hardware Requirements**:

NVIDIA Jetson Kit
Webcam or USB camera
Internet connection

**Software Requirements**:

-Python 3.x
-OpenCV
-TensorRT
-TensorFlow
-PyTorch
-YOLO V5

**Running the project**:

Connect the webcam or USB camera to the Jetson Kit.
Navigate to the project directory and run the main.py file using the command python main.py.
The program will open the camera stream, and the ID card classifier will start detecting and classifying ID cards in real-time.

**Model Training**:

The ID card classifier model can be trained on custom datasets.
To train the model, first, collect a dataset of ID card images.
Then, use transfer learning techniques to fine-tune pre-trained models such as VGG, ResNet, or Inception for classification.
Once the model is trained, save the model weights and update the model_path variable in main.py to use the new model for classification.

Happy classifying!
