# Plant Disease Classification
This project aims to develop a deep learning model that can classify three different types of potato diseases: Early Blight, Healthy, and Late Blight. The dataset used in this project is taken from the PlantVillage dataset.

# Dataset
The dataset consists of 6147 potato plant images, with each image having a resolution of 256x256 pixels. The dataset is divided into three folders: Training, Testing, and Validation. Each folder contains subfolders for the three classes: Early Blight, Healthy, and Late Blight.

# Getting Started
To run this project, you need to have Python and TensorFlow installed on your computer. You can install TensorFlow using the following command:

-pip install tensorflow
After installing TensorFlow, you can run the Jupyter notebook Potato_Disease_Classification.ipynb to train the model and make predictions.

# Model Architecture
The model used in this project is a Convolutional Neural Network (CNN) with four convolutional layers, two max-pooling layers, and two fully connected layers. The model is trained using the Adam optimizer with a learning rate of 0.0001 and a batch size of 32.

# Results
The model achieved an accuracy of 95% on the validation set, which shows that it is able to classify potato plant images with high accuracy. However, the model can still be improved by fine-tuning the hyperparameters and increasing the size of the dataset.

# Conclusion
This project demonstrates how deep learning can be used to classify potato diseases with high accuracy. The model can be used by farmers to detect diseases early and take appropriate measures to prevent crop loss.
