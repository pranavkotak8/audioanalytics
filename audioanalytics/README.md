AUDIO ANALYTICS PACKAGE VERSION 0.1 RELEASE 

----------------------------------------------

Overview of AudioAnalytics

This package is very unique one. It has its main goal towards
prediction of emotion in the audio file but has various other 
features also attached to it. The user can fetch the feature values dataframe
by providing the audio file. Features extracted in the dataframe, could 
be used in modeling or other visualizations. A short yet precise 
summary report is also an interesting part of this pacakage. It gives 
probabilities of various emotions predicted.

-----------------------------------------------

Usage Guidelines:

1) Importing the Package:

Code:
import audioanalytics

2) Extracting the feature values from the audio file.
Enter file path first.

Code:

file=r'path goes here'
from audioanalytics import extract_feature

extract_feature(file)

3) For Model_load

Code:

from audioanalytics import model_load

model_load()

4) For Prediction

Code:

from audioanalytics import predict
file_path=r'path goes here'
predict(file_path)

5) For Summary Report

Code:

from audioanalytics import summary
file_path=r'path goes here'
summary(file_path)

-------------------------------------------------------


Components of the AudioAnalytics Package:

1) Extract Feature - It will return the feature values in a Dataframe.
2) Model_Load - It loads the model from backend.
3) Predict - Predicts the Emotion by conducting the analysis of the provided audio.
4) Summary Report - A report where probabilities are displayed of 4 Emotions.

NOTE : THE AUDIO FILE INPUT FORMAT SHOULD BE .wav EXTENSION. ANY OTHER AUDIO FILE FORMAT IS NOT SUPPORTED FOR 0.1 VERSION. 

------------------------------------------------
