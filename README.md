# Driver-Alert-System-Using-CNN
## Overview

The Driver Alert System is an innovative project that utilizes Convolutional Neural Networks (CNNs) to detect driver drowsiness and prevent potential accidents. In recent years, CNNs have demonstrated remarkable success in identifying driver fatigue, making them a powerful tool for enhancing road safety.

### Key Features

- **Non-Contact Drowsiness Detection:** We've developed a non-contact technique to assess driver alertness levels and identify early signs of drowsiness during driving.

- **Real-Time Alerting:** When drowsiness or yawning is detected, the system issues a warning alarm to alert the driver, promoting immediate corrective action.

- **Eyes and Mouth State Detection:** Our CNN is designed to detect the states of the driver's eyes and mouth from Region of Interest (ROI) images.

- **Webcam Integration:** We use OpenCV to capture real-time images from a webcam, which are then fed into the deep learning model for analysis.

- **High Accuracy:** Through rigorous experimentation, we've achieved an accuracy rate exceeding 90% in detecting signs of driver fatigue.

## Methodology

Our system follows a comprehensive methodology to ensure accurate drowsiness detection:

1. **Data Collection:** We gather data using cameras and sensors, capturing facial images and physiological signals.

2. **Data Preprocessing:** To prepare the data for training, we perform tasks such as image resizing, data augmentation, and normalization.

3. **CNN Architecture:** We've designed a robust CNN architecture, including convolutional, pooling, and fully connected layers, to extract relevant features.

4. **Training the CNN:** The CNN is trained using preprocessed data, adjusting network parameters to optimize performance.

5. **Testing and Evaluation:** We evaluate the CNN's performance on a separate dataset to validate its accuracy and reliability.

6. **Deployment:** The trained CNN is integrated into a real-world system, incorporating sensors and actuators, and a user-friendly interface is designed.

## Technologies Used

Our project leverages several key technologies:

- **OpenCV:** For computer vision, image capture, and processing.
- **Keras:** A high-level neural networks API for building and training deep learning models.
- **NumPy:** For efficient numerical operations and data manipulation.
- **Pandas:** Data analysis and manipulation tools.
- **OS:** Interacting with the operating system at a low level.
- **Haar Cascade Features:** For real-time face detection.
- **Optimizers:** Including the ReLU activation function.
- **TensorFlow:** An open-source platform for machine learning.
- **Convolutional Neural Networks (CNNs):** Deep learning models for image analysis.

## Dataset

Our model is trained on a dataset obtained from Kaggle, containing four categories of images:

1) Closed_eyes - having 726 pictures
2) Open_eyes - having 726 pictures
3) Yawn - having 725 pictures
4) no_yawn - having 723 pictures

The Dataset was taken from Kaggle:(https://www.kaggle.com/datasets/dheerajperumandla/drowsiness-dataset)

The dataset includes 2,312 training images and 578 testing images.

We did about 50 epochs and got an accuracy level of 96%

![Screenshot 2023-09-07 145448](https://github.com/sriramm04/Driver_alert_System_Using_CNN/assets/129077845/16e50397-6e1c-4f79-9c00-484335c799f4)

![Screenshot 2023-09-07 145848](https://github.com/sriramm04/Driver_alert_System_Using_CNN/assets/129077845/10d0bfa7-0666-4fad-a783-4ac0767792e9)

![Screenshot 2023-09-07 145911](https://github.com/sriramm04/Driver_alert_System_Using_CNN/assets/129077845/0f760ac9-0fa0-4767-96b3-5eb3a72fd2b5)

## Conclusion

The Driver Alert System using CNN represents a significant advancement in road safety technology. By detecting and alerting drivers to signs of fatigue, it has the potential to save lives and prevent accidents. CNNs are proving to be a powerful tool in addressing driver drowsiness and enhancing road safety.
