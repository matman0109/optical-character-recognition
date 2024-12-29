Author: Matvii Repetskyi
Email: mrepetsk@u.rochester.edu

As can be seen on the screenshot attached to this project we may have images of handwritten characters, letters, or numbers that need to be labeled to build a machine learning model to predict the digit for a given image. The goal of this project is to determine whether clustering-based labeling improves the classification accuracy of a machine learning model. Information on the outcomes can be found at the end of the provided pdf or notebook.


The details about the dataset can be found below:
Each digit on the screenshot is constructed from an 8x8 grid that represents the values of the intensity of the pixel in the square. For example, a value of 0 represents no intensity (white) and 16 represents full intensity (black). Any number between 1 and 15 is a value of gray where 1 is very light and 15 is very dark.


List of files:
optical_character_recognition.pdf - main file showing all the work
optical_character_recognition.ipynb - same as pdf version but in notebook format
digits.pkl - the  dataset containing several; each row represents one of the digits in the data set and the columns represent the intensity values for the 64 squares that make up the digit
digits_labeled.pkl - the dataset containing labelled data for the image

