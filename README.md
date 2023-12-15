# 539-Project-Image-Classification

Our project’s goal is to develop a convolutional neural network model that will predict
plant diseases from a dataset containing thousands of images of both diseased and non-diseased
plant leaves. We plan to achieve an accuracy above 90% in predicting the diseases based upon
the capability of previous work done. Ideally, we would like to predict diseased vs. non-diseased
in addition to which disease type is present and what plant type is being looked at.


Dataset

The selected dataset is found on kaggle.com as “New Plant Disease Dataset,” published
by Samir Bhattarai. We have selected datasets with images of detached leaves on a plain
background, both healthy and diseased ones. These backgrounds help us better isolate and
extract features from the images. The dataset provided incorporates ~87,000 rgb images which
are categorized into 38 different classes. This dataset has also been divided into an 80/20 ratio of
training and validation set reducing the required cost for preprocessing and maintaining the
original directory structure. As of 10/21/2023 the dataset has 821 upvotes and has 255
documented uses in kaggle.com.
Plant Disease Dataset: This dataset is recreated using offline augmentation from the
previous version of the plant disease dataset. It also has a new directory containing 33 test
images enhanced for prediction [6].
Plant Village Dataset: The images in this dataset covers healthy and infected leaves of
crops plants of 14 different species and 26 different diseases [7].


Introduction and Setup: Explaining the purpose and scope of the notebook. It includes code for importing necessary libraries and setting up the environment.

Data Preparation: This section involves preparing the dataset for training and testing the ResNet model. It includes steps for loading the dataset, using PyTorch's Dataset and DataLoader classes, and applying transformations such as resizing and normalization.

Model Architecture: The architecture of the ResNet model. This includes defining the layers of the neural network, specifying hyperparameters, and configuring the model for the training process.

Training the Model: This section contains code for training the ResNet model. It includes the loss function, optimizer, and training loop where the model learns from the training data.

Model Evaluation: After training, it includes steps for evaluating the model's performance. This involves using a validation or test dataset to assess metrics like accuracy, loss, confusion matrix, ROC curve, and AUC.

Results Visualization: This section is dedicated to visualizing the results of the model's performance. This includes plotting graphs or charts to represent the accuracy, loss, confusion matrix, and ROC curves.
