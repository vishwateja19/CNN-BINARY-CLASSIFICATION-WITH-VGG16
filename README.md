## DEVELOPMENT OF CNN BINARY CLASSIFICATION USING VGG16(African and Asian elephants):
![App Screenshot](https://news.cgtn.com/news/78637a4e7841544e3549544f7963544d35497a4e31457a6333566d54/img/af79f91c6f5946639f690c5efaefef42/af79f91c6f5946639f690c5efaefef42.png)


Since we are using vgg16 for this model development instead of our own custom model 
so a brief introduction about vgg16:


VGG-16 is a convolutional neural network that is 16 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database . The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals.

for more information:
https://keras.io/api/applications/vgg/


![App Screenshot](https://media.geeksforgeeks.org/wp-content/uploads/20200219152327/conv-layers-vgg16.jpg)

In this is a  CNN model to classify images whether they are cat or dog . While the output is the accuracy, the main objective of this project is not to get a high accuracy but rather to learn how to use convolution neural network (CNN) for classification using tensorflow and instead of our own architecture which include kernel layers,
maxpooling layers of cnn and hidden layers of ann we use vgg16 architecture.











## DESCRIPTION





Since we use tensorflow framework so brief introduction about tensorflow.

TENSORFLOW:

TensorFlow is an open-source software library for deep learning and machine learning developed by Google Brain Team. It is used for a wide range of applications, including image and speech recognition, natural language processing, and computer vision. It is also used to create and train neural networks, which are the backbone of deep learning.


After collecting the data , i gave training and test data paths for image preprocessing using tensorflow framework ImageDataGenerator and then training the model withb vgg16 architecture instead of using our own architecture.Finally predicting the image whether image is African or Asian elephant.

i got the accuracy of 0.8000


The plot between training loss and training accuracy is:


![download plot](https://user-images.githubusercontent.com/114558376/218357699-46e69189-7f3d-4e86-8e21-aab722c47cdb.png)







 

 





## SKILLS

1.Python

2.Numpy

3.Pandas

4.Matplotlib

5.Seaborn

6.feature-engine

7.Sckit-learn

8.Statistics

9.Probability

10.Deep learning

11.Machine learning
## DATASET

follow this link:

 https://www.kaggle.com/datasets/vivmankar/asian-vs-african-elephant-image-classification
