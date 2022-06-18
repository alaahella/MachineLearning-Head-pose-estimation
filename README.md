# MachineLearning-Head-pose-estimation

##AFLW2000

AFLW2000-3D is a dataset of 2000 images. This dataset is used for evaluation of 3D facial landmark detection models. The head poses are very diverse and often hard to be detected by a CNN-based face detector. The 3D facial landmark is (YAW, PITCH, ROLL)

##steps:

1- Extract the facial landmarks using MediaPipe for the AFLW2000 dataset

2- use the angle data YAW, PITCH and ROLL values included in the data as the labels

3- Create Model to predict the YAW, PITCH and ROLL values of an image

4- Test the model on an image and draw predictions

created by me Alaa Hella
