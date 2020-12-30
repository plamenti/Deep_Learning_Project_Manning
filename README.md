### Deep Learning Live Project

#### Project outline
The project is broken into 6 parts.

1. Setting up the Google Colab Notebook
2. Collecting and Cleaning Data
3. Create a Neural Netwok
4. Common Training Errors
5. Hyper Parameter Tuning
6. Deploying a Trained Network

#### Prerequisites
The liveProject is for beginner or intermediate Python programmers with a desire to pick up some data science.

TOOLS
1. Basics of Python
2. Basics of pandas
3. Basics of Google Colab
4. Basics of TensorFlow and Keras

TECHNIQUES
Basics of machine learning

#### Python libraries and setup
Google Colab notebook / Jupyter Notebook / another Python IDE, that is fine as well.

Python: Version 3.6.

TensorFlow: Version 2.2.

pandas: Version 1.0.3.

Matplotlib: Version 3.2.1.


#### CLASSIFICATION AND REGRESSION GLOSSARY

***Sample*** or ***input*** — One data point that goes into your model.

***Prediction*** or ***output*** — What comes out of your model.

***Target*** — The truth. What your model should ideally have predicted, according to an external source of data.

***Prediction error*** or ***loss value*** — A measure of the distance between your model’s prediction and the target.

***Classes*** — A set of possible labels to choose from in a classification problem. For example, when classifying cat and dog pictures, *dog* and *cat* are the two classes.

***Label*** — A specific instance of a class annotation in a classification problem. For instance, if picture #1234 is annotated as containing the class *dog*, then *dog* is a label of picture #1234.

***Ground-truth*** or ***annotations*** — All targets for a dataset, typically collected by humans.

***Binary classification*** — A classification task where each input sample should be categorized into two exclusive categories.

***Multiclass classification*** — A classification task where each input sample should be categorized into more than two categories: for instance, classifying handwritten digits.

***Multilabel classification*** — A classification task where each input sample can be assigned multiple labels. For instance, a given image may contain both a cat and a dog and should be annotated both with the *cat* label and the *dog* label. The number of labels per image is usually variable.

***Scalar regression*** — A task where the target is a continuous scalar value. Predicting house prices is a good example: the different target prices form a continuous space.

***Vector regression*** — A task where the target is a set of continuous values: for example, a continuous vector. If you’re doing regression against multiple values (such as the coordinates of a bounding box in an image), then you’re doing vector regression.

***Mini-batch*** or ***batch*** — A small set of samples (typically between 8 and 128) that are processed simultaneously by the model. The number of samples is often a power of 2, to facilitate memory allocation on GPU. When training, a mini-batch is used to compute a single gradient-descent update applied to the weights of the model.

