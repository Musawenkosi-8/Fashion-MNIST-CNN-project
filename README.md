🧠 Fashion MNIST Clothing Classification with Convolutional Neural Networks (CNN)

This project demonstrates how to use deep learning techniques to accurately classify grayscale images of clothing into one of 10 categories using the Fashion MNIST dataset. The model is built using TensorFlow and Keras, and trained on 60,000 training images and evaluated on 10,000 test images.
📂 Dataset

The Fashion MNIST dataset is a popular benchmarking dataset consisting of 28x28 grayscale images of clothing items such as shirts, trousers, sneakers, etc., serving as a more challenging drop-in replacement for the classic MNIST digit dataset.

    📈 10 classes

    🧵 70,000 total images

    📸 Image size: 28x28 (grayscale)

🛠️ Project Objectives

    Build a CNN from scratch using TensorFlow/Keras

    Train the model to classify images into 10 clothing categories

    Evaluate the model using precision, recall, F1-score, and confusion matrix

    Visualize model performance and errors

    (Optional) Deploy the model as a web app using Streamlit

🧱 Model Architecture

    Conv2D → ReLU → MaxPooling

    Conv2D → ReLU → MaxPooling

    Flatten → Dense(64) → Output(Dense(10), Softmax)

This structure is designed to extract hierarchical spatial features and classify them effectively using fully connected layers.
📊 Evaluation Metrics

    Test Accuracy: ~90%+

    Classification Report: Includes precision, recall, and F1-score for each class

    Confusion Matrix: Visual comparison of predicted vs. true labels

🖼️ Visualizations

    Loss and accuracy plots over training epochs

    Confusion matrix heatmap

    Bar chart comparing class-wise precision, recall, and F1-score
