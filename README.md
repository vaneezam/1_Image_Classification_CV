# Image Classification

## Task-1 : Human Classification / Detection using Histogram of Gradients -> "HoG_Human_Classification.ipynb"
Human Detection is a branch of Object Detection. Object Detection is the task of identifying the presence of predefined types of objects in an image. This task involves both identification of the presence of the objects and identification of the rectangular boundary surrounding each object (i.e. Object Localisation). An object detection system which can detect the class “Human” can work as a Human Detection System.<br>
Human detection is an essential and significant task in any intelligent video surveillance system, as it provides the fundamental information for semantic understanding of the video footages. It has an obvious extension to automotive applications due to the potential for improving safety systems. Many car manufacturers (e.g. Volvo, Ford, GM, Nissan) offer this as an ADAS option in 2017. Some of the applications be given as;<br>
o Self-driving cars: Identifying pedestrians on a road scene<br>
o Security: Restrict access for certain people to certain places<br>
o Retail: Analysing visitors behaviour within a supermarket<br>
o Fashion: Identify specific brands and persons who wear them<br>
## Histogram of Oriented Gradients<br>
HOG is an acronym for Histogram of Oriented Gradients. It's an algorithm called a feature descriptor which helps with object detection in computer vision and image processing models. HOG is a kind of feature descriptor that counts occurrences of gradient orientation in localized portions of an image.<br>
<br>
Download the INRIA Person Dataset Samples from here (https://drive.google.com/file/d/1pDr3138jwk8WuHF2CFGVlKbKvt27hMIH/view?usp=sharing ).<br>
Compute HoG features and train two classifiers i.e SVM and Random Forest. You can use sklearn library’s function feature.hog to compute HOG features. Experiment with different parameters and report the results obtained after training of both the classifiers i.e. Linear SVM and Random Forest Classifier. The classifiers are also available in sklearn library.
You may use sklearns’ joblib package to save and reload your trained classifier model.

## Task-2 : Image Classification Using Bag of Visual Words -> "BoW Image Classification.ipynb" , "BoW Image Classification _ Splitting folders.ipynb"
The concept of “Bag of Visual Words” is taken from the related “Bag of Word” concept of Natural Language Processing. In the bag of word model, the text is represented with the frequency of its word without taking into account the order of the words (hence the name ‘bag’). The main idea behind the counting of the word is: Documents that share a large number of the same keywords, regardless of the order the keywords appear in, are considered to be relevant to each other.<br>
 "BoW Image Classification.ipynb" contains Object Classification using BOW <br>
 "BoW Image Classification _ Splitting folders.ipynb" contains Classification of Flower dataset by first splitting each class in folder in TEST AND TRAIN DATA using BOW <br>
