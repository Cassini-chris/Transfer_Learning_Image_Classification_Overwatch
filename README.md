# Transfer_Learning_Image_Classification_Overwatch

This repo holds the code for a Overwarch-Classification Model using Transfer Learning via TensorFlow Hub modules.
The Model is saved as HDF5 and can be loaded via Keras model.load('model'). 

## [>> Download Model](https://storage.googleapis.com/epicml_public_bucket/01_ml_models/05_overwatch_model/overwatch_model.h5 "Overwatch Model")

In case you want to retrain the model - I have uploaded the manual collected training / test data to Kaggle Dataset (~1500 image files). #### [>> Download Training Data](https://www.kaggle.com/magicchris/overwatch-characters "Overwatch Training Data")

#### The project is for educational purposes: 
- Learn how to build an image classification model
- Get familiar with Transfer Learning / TensorFlow Hub 
- Get familiar with Kearas & TensorFlow 

#### Image classification problem:
Image classification is a supervised learning problem. We define a set of target classes (in our case Overwatch Characters), and train a model to recognize them using labeled example photos. In our example, we will make use of TensorFlow 2.x in order to build, train, and optimize our model.

![alt text](https://github.com/cassini-chris/Transfer_Learning_Image_Classification_Overwatch/blob/main/_GITHUB/readme/images/overwatch_background.png?raw=true)
