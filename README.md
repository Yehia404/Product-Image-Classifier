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
![data](https://github.com/Yehia404/Product-Image-Classifier/assets/121027774/746ea4ac-419f-43bc-a839-12101a68be97)

- Splitting data into train, validation, and test data.
- Building Deep Learning Model and adding to the model Conv2D, Maxpooling2D, Flatten, and Dense Layers then compiling it.
![model](https://github.com/Yehia404/Product-Image-Classifier/assets/121027774/edb08ecb-6b26-4c0b-acf1-728e89491450)

- Training and validating model with training and validation data.

![train](https://github.com/Yehia404/Product-Image-Classifier/assets/121027774/309faa91-d1e3-4b4d-a2fe-a3b1670ee93b)

- Plotting Loss and Accuracy to check the decrease in loss and increase in accuracy.

![loss](https://github.com/Yehia404/Product-Image-Classifier/assets/121027774/86c188aa-1435-42d2-a9c3-565600135021)
![accuracy](https://github.com/Yehia404/Product-Image-Classifier/assets/121027774/113d7e5b-59d8-4593-9290-80b268e58349)

- Evaluating the model using Precision, Recall and BinaryAccuracy.
- Testing Model with photos it has never seen stored in **manualtest** folder
![test](https://github.com/Yehia404/Product-Image-Classifier/assets/121027774/9cd5437d-e73f-40a6-a019-aa057144476f)

# Video


https://github.com/Yehia404/Product-Image-Classifier/assets/121027774/3cd0133c-daab-406f-8747-16a9927aec1e




