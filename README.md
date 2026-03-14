# Traffic_Sign_Classification

TRAFFIC SIGN CLASSIFICATION USING CNN

Project Overview
This project is a Deep Learning based Traffic Sign Classification system. 
It uses a Convolutional Neural Network (CNN) to identify and classify traffic signs from images.

The model is trained on a dataset containing 43 different classes of traffic signs. 
A graphical user interface (GUI) built using Tkinter allows users to upload an image and get the predicted traffic sign.

-------------------------------------

Technologies Used

Python
TensorFlow / Keras
OpenCV
NumPy
Pillow (PIL)
Matplotlib
Tkinter

-------------------------------------

Dataset

The project uses the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

Dataset details:
- 43 different traffic sign classes
- Thousands of labeled training images
- Images resized to 30x30 pixels for training

-------------------------------------

Project Structure

Traffic-Sign-Classifier
|
|-- train_model.py
|-- traffic_classifier.h5
|-- gui_classifier.py
|-- train/
|-- Test.csv
|-- README.txt

-------------------------------------

Model Architecture

The CNN model contains:

1. Convolutional Layers
2. Max Pooling Layers
3. Dropout Layers
4. Fully Connected Dense Layers
5. Softmax Output Layer (43 classes)

The model is trained using:
Loss Function: Categorical Crossentropy
Optimizer: Adam
Epochs: 15

-------------------------------------

How the System Works

1. Images are loaded from the dataset.
2. Images are resized to 30x30 pixels.
3. Pixel values are normalized.
4. The CNN model learns features from the images.
5. The trained model predicts the traffic sign class.
6. The GUI displays the predicted traffic sign label.

-------------------------------------

Running the Project

Step 1: Install required libraries

pip install tensorflow
pip install numpy
pip install pillow
pip install matplotlib
pip install opencv-python

Step 2: Train the model

python train_model.py

Step 3: Run the GUI application

python gui_classifier.py

Step 4: Upload a traffic sign image and click "Classify Image".

-------------------------------------

Example Output

Uploaded Image -> Model Prediction

Example:
Stop Sign
Speed Limit (50km/h)
No Entry

-------------------------------------

Future Improvements

Add real-time traffic sign detection using camera
Improve model accuracy
Deploy the model as a web application
Add support for video input
