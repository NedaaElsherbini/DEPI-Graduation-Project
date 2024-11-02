# FaceLock Attendance System

[Watch the video](file:///C:/Users/dell/Downloads/WhatsApp%20Video%202024-10-23%20at%2010.45.22%20AM.mp4)

## Data Collection & Preparation

In this phase, we collected images of attendees under varying lighting conditions and angles. The dataset was organized as follows:

- **Data Splitting**: The collected images were split into two folders:
  - **Train Images**: Contains images used for training the model.
  - **Test Images**: Contains images used for testing the model.
    
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


