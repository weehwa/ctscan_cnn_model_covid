#**Problem Statement:**

**To Predict if the CT Scan is positive or negative cases of Covid.**

Covid19 had been a issue with the world, as the virus had affected varies countires around the global. Buisnesses and individuals are lossing customers as governments are issuing stricter measures to counter and prevent the spread of the virus. 

For this project, we will be focusing on Convolutional neural network(CNN) to predict if the CT Scan image is a positive or Negative case of Covid19.

Data:\
For this predictive model we downloaded the data from kaggle ref: https://www.kaggle.com/c/covidct \
We have a total of: \
- Covid CT Scan Images: 1252 (png)
- Non-Covid CT Scan Images: 1230 (png)

We will divide them into 3 folders manually: \
1) train: (to train the model)
- Covid: 992 images
- Non-Covid: 975 images

2) val: (to validite the model after each epoch)
- COVID: 248 images
- Non-Covid: 244 images

3) test: (to manually test and observe the result)
- COVID : 12 images
- Non-Covid : 10 images 

We will break into 3 Parts for this project namely:\
Part A : Observe the CT Scan and to deferentiate the difference visually. \
Part B : We wil test our 3 models namely:\
1) VGG16\
2) InterceptionV3\
3) Resnet50\
and select the best one for hyperparameter tuning.\
Part C : We wil use the best mdoel to fine tune the training rate and use the best model. 

To aviod bias, we will be using 50 epoch to train all the models and confusion metrix from prediction of the test dataset. Accuracy and validity acccuracy are the measurements for the performance of the model.
