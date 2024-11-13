# 💻  Driver_Drowsiness_Detection_Transfer_Learnig
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)

# Introduction:

Driver drowsiness detection is a system designed to monitor a driver's alertness level and detect signs of drowsiness or fatigue. The goal of such a system is to prevent accidents caused by drivers who are not fully attentive while driving.

These systems typically use computer vision techniques to analyze the driver's face and monitor their eyes and facial expressions. Common approaches include:

Eye Tracking: Monitoring the driver's eye movements to detect patterns indicative of drowsiness, such as slow blinking or closing of eyes for an extended period.

Facial Recognition: Analyzing facial features to detect changes in expression or head position that may indicate drowsiness.

Machine Learning: Using machine learning algorithms to train a model on a dataset of drowsy and alert driving behaviors, allowing the system to classify current behavior.

Alert Systems: Providing alerts to the driver, such as sound or vibration, when signs of drowsiness are detected, to prompt them to take a break or rest.



## Install the Packages which is used in Package
    pip install keras
    pip install matplotlib
    pip install numpy
    pip install opencv-python
    pip install keras
    pip install numpy
    pip install pygame


# 📊 DOWNLOAD THE DATASET FOR THE GIVEN LINK:

For a driver drowsiness detection project, you would typically need a dataset of images or videos containing examples of both drowsy and alert driving behaviors.Download the data-set

    https://www.kaggle.com/datasets/serenaraju/yawn-eye-dataset-new/data 

This for the Train

##### <i>train_batch = generator("ADD THE DATA_SET FILE OF TRAIN HERE", shuffle=True, batch_size=BS, target_size=TS)</i>

This for the Test

##### <i>valid_batch = generator("ADD THE DATA_SET FILE OF TEST HERE", shuffle=True, batch_size=BS, target_size=TS)</i>

### Then It create the model file after training the dataset.

##### <i>cnn_model.save("models/cnnCat2.h5", overwrite=True)</i>

When the Eyes are closed, when score is greater than 15, Then it create Red color in border Then it create the sound 

  and also capture the image for the proof.

When he open the Eyes then score reduce .

