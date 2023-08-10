# potato-leaf-disease-classification-

# Introduction
Welcome to the Potato Leaf Disease Classification project! This repository contains code and resources for accurately identifying and classifying diseases affecting potato leaves. The health of potato plants is crucial for ensuring a stable food supply, and early detection of diseases can significantly contribute to preventing yield loss.

# Dataset 

# Dataset credits: https://www.kaggle.com/arjuntejaswi/plant-village

The dataset used for this project consists of high-quality images of potato leaves afflicted by various diseases, as well as images of healthy potato leaves for comparison. The dataset is carefully curated and annotated to provide a diverse set of examples for training and evaluation.

# Installation
To set up the project environment and dependencies, follow these steps:

1.Clone this repository: git clone https://github.com/satheeshbhukya/potato-leaf-disease-classification-
2.Navigate to the project directory: cd potato-leaf-disease-classification
3.Create a virtual environment: python -m venv venv
4.Activate the virtual environment:
 > On Windows: venv\Scripts\activate
 > On macOS and Linux: source venv/bin/activate
5.Install dependencies: pip install -r requirements.txt

# Usage 
To use the trained model for potato leaf disease classification, follow these instructions:

1.Prepare your input image(s) of potato leaves.
2.Run the classification script: python classify.py --image path_to_your_image.jpg
3.The script will output the predicted disease class for the input image.

# Model
We employed a deep convolutional neural network (CNN) architecture to train a robust model for potato leaf disease classification. The model has been trained on the provided dataset using transfer learning, leveraging a pre-trained network to achieve high accuracy even with limited labeled data.

# Results
Our trained model achieves an impressive accuracy of over 99.88% on the validation set, demonstrating its effectiveness in identifying various potato leaf diseases. Detailed performance metrics and visualizations can be found in the Potata.ipynb directory.

# Contributing
Contributions to this project are welcome! Whether you want to add more disease categories, improve the model's performance, or enhance the documentation, please feel free to submit a pull request.

# License
This project is licensed under the MIT License, which means you're free to use, modify, and distribute the code as you see fit.





