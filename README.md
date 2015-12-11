# CS205 Final Project - BEES ? BEES !
### Project Name : Image Classification using Apache Spark
##### 1) Team member : Xiowen Chang, Jeewon Hwang, Xingchi Dai
##### 2) Website : [http://cs205-beesbees.weebly.com/](http://cs205-beesbees.weebly.com/) 
##### 3) Sceencast : [https://youtu.be/dSCy9Fxtr0s](https://youtu.be/dSCy9Fxtr0s)
##### 4) Database we used : [Bee Database (5,000 images)](http://www.drivendata.org/competitions/8/data/)
(Since this Bee Database is over the limit of github upload size, we give the link to the database instead. Other datasets, such as train data labelled by ourselves are uploaded together in github repo.)

### How to Run our code
Our code is written by IPython Notebook. (
that describes the code and application files, and how your program should be run.
In the submitted file, you will find ipython notebook and python file. Please use ipython notebook to grade.
You should be able to open the file by typing "ipython notebook" in your terminal. 
One PDF of the ipython notebook is also submitted.
All results have been shown. You can also run everything starting from beginning, but doing so might erase our previous 
results. Also, you need to download some packages before running. please use "conda" commands, such as: openCV, Oputunity, Pyspark etc.
We commented our code, so you should find it easy to read and follow our steps.
Our video has been submitted to Youtube.
Our website contains discussions of implementation, conclusion and code performance. So, you might find that useful when you grade. 

Thanks again



## Overview of our Project
##### Background and Motivation
Face recognition has become one of the most popular research areas, as faces’ expressions contain much information neuroscientists and psychologists are interested in. It is also one of the most successful applications of computer vision and machine learning researches. As such, the team is motivated to use what CS109 has taught, such as PCA, KNN, SVN, etc. in the class to implement a simple, yet practical, face detection and recognition project. The expected background researches for this project covers advanced classification algorithms and some tools to evaluate/estimate performance, such as Principal-Component-Analysis (PCA), K-Nearest-Neighbors (KNN) and Linear-Support-Vector-Machine (Linear SVM), Confusion Matrix and ROC curve.

##### Project Objectives
The goal of this project is to finish a classification algorithm to detect and distinguish objects(faces) in images. During the project, the team members will consolidate the knowledge given in classes and integrate them to deliver a completed, working, interesting project. The project itself is not a breakthrough technological achievement, yet it is an opportunity for team members to review, learn and think.

##### Feature:
1: Face detection: detect the face in a photo.

2: Face recognition/classification: classify the gender of the detected face.

##### Design Overview
1: Face detection: The OpenCV(Open Source Computer Vision) module would be used to detect the face.

2: Face recognition: PCA(Principal Component Analysis) would be used to reduce the dimension. KNN(K-Nearest-Neighbors), SVM(Support Vector Machines) and Logistic Regression would be used to do the gender classification.

3: Parameterization: k-fold cross-validation approach would be applied to avoid over-fitting scenario.

4:Model assessment: AUROC (area under ROC curve) will be used to evaluate the accuracy of results and the performance of algorithms.

##### Verification
Train/Test data: data will be divided into the train dataset and the test dataset. The train dataset would be used to develop the algorithm and the test dataset would be used to evaluate the performance of the algorithm.



