# COVID19_Pneumonia_Detection
Detects Covid-19 Pneumonia signs from CT Scan Images by a CNN Model. The model have a uniform dataset of 764 Images of CT Scan which consist 349 Images of Covid-19 Pneumonia affected patients and remaining shows normal patient scans.

Here are some CT-Scans of lungs:

COVID19 Patient Scan:

![alt text](https://github.com/aniruddh-1/COVID19_Pneumonia_detection/blob/master/ct_scan_dataset/covid19/168%20.png "CT Scan1")






Normal Patient Scan:

![alt text](https://github.com/aniruddh-1/COVID19_Pneumonia_detection/blob/master/ct_scan_dataset/normal/80%20.png "CT Scan2")

The dataset was taken from the following source : https://github.com/UCSD-AI4H/COVID-CT/tree/master/Images-processed

You can also download the dataset directly from above link or can go through my dataset where I have indexed all the images and converted them into same format(PNG).
I have used tensorflow library for training a binary classification model of CT Scans using Convolutional Neural Network. The graph of model is as follows:
![alt text](https://github.com/aniruddh-1/covid19-detection/covid19_dataset/tensorboard_logs/cnn_architecture.png "CNN")

I have also uploaded 2 trained models on above graphs:
* Model 1: Validation Accuracy - 80.82%, Validation Loss - 50.10%
* Model 2: Validation Accuracy - 78.00%, Validation Loss - 47.28%

As the dataset of CT Scans of COVID19 patients is limited, the model seems to overfit, so you can also contribute by sharing any ideas or providing more dataset for this repository by sending the information on my email.

As the dataset of CT Scans of COVID19 patients is limited, the model seems to overfit, so you can also contribute by sharing any ideas or providing more dataset for this repository by sending the information on my [email](https://github.com/aniruddh-1).
