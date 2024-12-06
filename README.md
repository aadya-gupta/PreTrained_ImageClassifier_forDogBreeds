# Pre-Trained Image Classifier for Dog Breeds

Recently I was accepted into the AWS AI/ML Scholarship Program. 

<img src="IMG_3380.png" alt="Recepient Badge" width="450" height="300"> <img src="IMG_3379.png" alt="Congrats email" width="300" height="300">

The AWS AI & ML Scholarship program, in collaboration with Udacity, is an AI/ML-focused scholarship program providing 2,500 Udacity nanodegree scholarships annually, as well as a mentorship program, to students. Find out more about the program [here](https://aws.amazon.com/machine-learning/scholarship/).

As part of the program we have to build two projects. 
A few days ago I completed the very first project which was to use a pre-trained image classifier for dog-breeds. 

<img src="IMG_3770.png" alt="Project Completion Badge" width="300" height="300">

Here I have shared the exact project we had to build along with the project's description, our tasks and important notes. 

P.S. - The project contains files that end with "hints". These were provided to us for guidance in case we got stuck with any function. 

## Description 
Your city is hosting a citywide dog show and you have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. The registration system tags the images based upon the biographical information.

Some people are planning on registering pets that aren’t actual dogs.

You need to use an already developed Python classifier to make sure the participants are dogs.

Note: you DO NOT need to create the classifier. It will be provided to you. You will need to apply the Python tools you just learned to USE the classifier.

## Tasks
- Using your Python skills, you will determine which image classification algorithm works the "best" on classifying images as "dogs" or "not dogs".
- Determine how well the "best" classification algorithm works on correctly identifying a dog's breed. If you are confused by the term image classifier look at it simply as a tool that has an input and an output. The Input is an image. The output determines what the image depicts. (for example, a dog). Be mindful of the fact that image classifiers do not always categorize the images correctly.
- Time how long each algorithm takes to solve the classification problem. With computational tasks, there is often a trade-off between accuracy and runtime. The more accurate an algorithm, the higher the likelihood that it will take more time to run and use more computational resources to run.

## Important Notes
For this image classification task, you will be using an image classification application using a deep learning model called a convolutional neural network (often abbreviated as CNN). CNNs work particularly well for detecting features in images like colors, textures, and edges; then using these features to identify objects in the images. You'll use a CNN that has already learned the features from a giant dataset of 1.2 million images called ImageNet(opens in a new tab). There are different types of CNNs that have different structures (architectures) that work better or worse depending on your criteria. With this project, you'll explore the three different architectures (AlexNet, VGG, and ResNet) and determine which is best for your application.

We have provided you with a classifier function in classifier.py that will allow you to use these CNNs to classify your images. The test_classifier.py file contains an example program that demonstrates how to use the classifier function. For this project, you will be focusing on using your Python skills to complete these tasks using the classifier function.

