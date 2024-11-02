# FaceLock Attendance System
https://github.com/user-attachments/assets/0cb49a4b-2558-4d38-927e-5aafcd394ce2
## Data Collection & Preparation

In this phase, we collected images of attendees under varying lighting conditions and angles. The dataset was organized as follows:

- **Data Splitting**: The collected images were split into two folders:
  - **Train Images**: Contains images used for training the model.
  - **Test Images**: Contains images used for testing the model.
### Note: We used a Dataset of people on the system, so we can't share it.
    
## Model Development

In this phase, we trained the model using dlib's state-of-the-art face recognition built with deep learning.

### FaceNet Deep CNN Algorithm
An advanced architecture for generating high-quality face embeddings.

> **How it works?**
> 
> It maps each face image into a 128-dimensional vector (embedding).
-  If two images belong to the same person, their embeddings will be close together in this high-dimensional space, while embeddings of different people will be far apart.

## Model Deployment

After training, we deployed the model on Hugging Face, allowing easy access and integration for various applications.

This deployment enables the model to be hosted, shared, and utilized across different platforms seamlessly.

## System

[FaceLock Attendance System on Hugging Face](https://huggingface.co/spaces/Nada-Medhat/FaceLock_AttendanceSystem)


