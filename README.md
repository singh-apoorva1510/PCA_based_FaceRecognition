# PCA_based_FaceRecognition

Abstract:

Every human being has got a unique face. Face is a complex and multi-dimensional entity which changes in a
certain limit with different expressions and makeover. Efficient facial recognition is one of the important problem
being solved now days. It is an important part of any biometric based authentication. Although with the advent
of ML/AI in recent years, deep neural networks and other similar approaches have already showcased accuracy
up to 99% in this field but these methods primarily require huge amount of data to train to provide such accuracy.
Another limitation is, they are computationally expensive solution for Face Recognition and can’t be deployed
on low end devices. PCA based Face Recognition can be efficiently used in such cases. The purpose of this project
is to analyze how a PCA based facial recognition system can be built from scratch and also identify what
parameters of the system are optimal. The dimensionality reduction principle of PCA accounts for the smaller
face space while still preserving the integrity of the data.


Dataset Description:

The dataset to be used is AT&T "The Database of Faces". It contains 10 different facial images of 40 different
people. The 10 different images of a particular person were taken by varying light, facial expressions, facial details
etc. In addition to above dataset, the plan is to also collect my own data set of different people and then preprocess
it to be used in the proposed system.


Statistical Model:

This approach treats face recognition as a two-dimensional recognition problem. In this scheme face recognition
is done using Principal Component Analysis (PCA). Face images are projected onto a face space that encodes
best variation among known face images. The face space is defined by eigenface which are eigenvectors of the
set of faces, which may not correspond to general facial features such as eyes, nose, lips. The eigenface approach
uses the PCA for recognition of the images. The system performs by projecting pre-extracted face image onto a
set of face space that represent significant variations among known face images. Face will be categorized as
known or unknown face after matching with the present database. If the user is new to the face recognition system
then his/her template will be stored in the database else matched against the templates stored in the database.


Deliverables and Ouput:

The system will be tested for its accuracy with the use of test dataset. The test dataset will be different from the
training dataset. The goal is to analyze the trade-off between number of principal components used for data
representation versus the accuracy achieved using them. Comparison data for different combination will be shown
using graphs/charts etc.


Usage: 

python eigenFace.py
