# Early-Blindness-Diabetic-Retinopathy-Detection
This GitHub repository contains the code and resources for an early detection system for Blindness and Diabetic Retinopathy. The goal of this project is to classify retinal images into three classes: "NO DR" (No Diabetic Retinopathy), "Moderate DR" (Moderate Diabetic Retinopathy), and "Severe DR" (Severe Diabetic Retinopathy).

# Live classification
1. Moderate DR case
![Moderate DR classification](https://github.com/Roodraps/Early-Blindness-Diabetic-Retinopathy-Detection/assets/113835698/5617db6d-f6e6-4782-947b-54a20e3626c7)

2. NO DR case
![NO DR Classification](https://github.com/Roodraps/Early-Blindness-Diabetic-Retinopathy-Detection/assets/113835698/5c7d2568-7e77-462d-b73d-c27b850fc84b)

3. Sever DR case
![Severe case classification](https://github.com/Roodraps/Early-Blindness-Diabetic-Retinopathy-Detection/assets/113835698/b3767926-68d6-48a7-8399-4ec735cb3626)



# Model Performance
The trained model achieved a training accuracy of 82.2% and a model testing accuracy of 74.81% on the provided dataset. The model was developed using deep learning techniques and leverages convolutional neural networks (CNNs) to extract features from retinal images.

# Edge Device Deployment
The trained model has been deployed on an edge device called Raspberry Pi 4. This deployment allows for real-time classification of retinal images directly on the edge device, enabling faster and more efficient processing without relying on cloud or remote servers.

# Real-time Classification via Mobile Phone
To facilitate real-time classification, a mobile application has been developed. The mobile application integrates with the deployed model on the Raspberry Pi 4. Users can initiate the classification process by scanning a QR code generated by the Edge Impulse platform. This enables quick and convenient classification of retinal images using a mobile phone.


# Getting Started
To get started with this project, please refer to the README.md file in each directory for specific instructions on dataset preparation, model training, deployment on Raspberry Pi 4, and using the mobile application for real-time classification.
