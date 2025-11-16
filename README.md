# Deep-Learning-Model-for-Potato-Leaf-Disease-Detection
A deep learning CNN model was built using TensorFlow/Keras to classify images with high accuracy. The trained model was deployed locally using FastAPI, allowing users to upload images and receive real-time predictions through a simple web interface.

This project focuses on building and deploying a Deep Learning–based Image Classification system using TensorFlow, Keras, and FastAPI. The core objective of the project is to develop a Convolutional Neural Network (CNN) capable of learning visual patterns from images and accurately classifying them into predefined categories. The model is trained on a labeled dataset, where each image belongs to a specific class. Through convolution, pooling, and dense layers, the CNN extracts meaningful features such as edges, shapes, and textures, enabling it to make reliable predictions.

The project involves several important steps, starting with data preprocessing, where images are resized, normalized, and split into training and test sets. To improve the model’s performance and prevent overfitting, techniques such as data augmentation and dropout were applied. The trained model is saved in a .keras format, allowing it to be reused without retraining.

A key highlight of this project is the implementation of a local web interface using FastAPI. The API loads the trained CNN model and provides an endpoint where users can upload images for real-time classification. FastAPI ensures fast response times, easy integration, and a clean structure for handling requests. The backend processes the uploaded image, performs preprocessing, feeds it to the model, and returns the predicted class along with the confidence score.

This project demonstrates strong skills in deep learning, model optimization, API development, and deployment. It can be extended for real-world applications such as object recognition, medical imaging, and automated quality inspection.
