# Melanoma_SkinCancer_Detection

## Problem Statement
In this task, you'll use a customised convolutional neural network in Tensorflow to create a multiclass classification model.

Create a CNN-based model that accurately detects melanoma, which is the problem. If melanoma is not found in its early stages, it can be fatal. It is responsible for 75% of skin cancer fatalities. A system that can analyse photos and notify doctors of the existence of melanoma might potentially eliminate the need for a lot of manual diagnosis work.
The International Skin Imaging Collaboration (ISIC) created the collection, which comprises of 2357 photographs of both malignant and benign oncological illnesses. All photos were sorted using the ISIC classification, and each subset was given an equal amount of images.

The data set contains the following diseases:


1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

## Project Schedule
1. Defining the train and test picture paths for data reading and data understanding
2. Create a train & validation dataset with a batch size of 32 from the train directory.
3. Additionally, be sure to 180*180 resize your photographs.
## Dataset visualisation: 
1. Write a programme to display a single instance of each of the dataset's nine classes.
2. Building and training models: 
3. Make a CNN model that can precisely identify the nine classes that are present in the dataset. 
4. Rescale photos to normalise pixel values between (0,1) when developing the model.
5. For model training, pick an appropriate optimiser and loss function. 20 iterations of the model training
6. Write your conclusions once the model has been fitted, and look for any indications of overfitting or underfitting.
7. Select the best data augmentation technique toi dentify and fix under- or overfitting Building models and training using the augmented data:
8. Make a CNN model that can precisely identify the nine classes that are present in the dataset. Rescale photos to normalise pixel values between (0,1) when developing the model.
