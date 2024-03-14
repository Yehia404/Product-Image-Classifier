# Product-Image-Classifier
The Product Image Classifier classifies the products into 4 classes which are:
1. Accessories
2. Beauty
3. Fashion
4. Nutrition

**The ProductClassifier.ipynb is organized with headings explaining each step**
In the process of making the classifier certain steps must be taken in order to achieve completion which are:
- Importing Dataset in **data** folder and organizing them into folders according to the classes they belong to.
- Remove dodgy images by specifying certain extensions and anything else remove it.
- Loading dataset in data variable and iterating on it then dividing it by 255 to scale them between 0 and 1 and include with them the class they belong to in one_hot encoding.
- Splitting data into train, validation, and test data.
- Building Deep Learning Model and adding to the model Conv2D, Maxpooling2D, Flatten, and Dense Layers then compiling it.
- Training and validating model with training and validation data.
- Plotting Loss and Accuracy to check the decrease in loss and increase in accuracy.
- Evaluating the model using Precision, Recall and BinaryAccuracy.
- Testing Model with photos it has never seen stored in **manualtest** folder

