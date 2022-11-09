# traffic-sign-classification
In this project, I will use a CNN to build, train and test a traffic sign classification model. I will build this model using TensorFlow and Keras. 

## Scope
This model can be used in self driving cars which will enable them to automatically recognize traffic signs similarly the driver alert system inside cars will help protect dricers by understanding the traffic signs around them.

## Dataset
https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

## Steps
1. Finding Data on Kaggle and laoding it into Google Colab.
2. Preprocessing the images and visualizing them.
3. Finding out the mean of the dimensions and resizing all images accordingly. 
4. Comverting the images into a numpy arrray and normalize them. 
5. Checking class imbalance.
6. Splitting the data and performing one-hot encoding.
7. Creating the model architecture, compiling the model and then fitting it. 
8. Plotting the accuracy and loss against each epoch. 
9. Preprocessing the test data and make predictions on it. 
10. Visualizing the original and predicted lables for the test images. 

## Run
1. Clone the repository or download the zip file.
2. Unzip the file and load the `.ipynb` file to google colab.
3. Connect to runtime and run all cells.

## Output
![image](https://user-images.githubusercontent.com/50231750/200907915-98b0938a-36e3-42d7-be34-b4466ca01e69.png)

## Accuracy per Epoch
![image](https://user-images.githubusercontent.com/50231750/200908696-78f72708-a185-4f05-a873-e6afaa4aef11.png)

## Loss per Epoch
![image](https://user-images.githubusercontent.com/50231750/200908890-c6ec1a84-d20a-4c1f-a6f9-5cd600c3ab2e.png)


## Conclusion
We started with downloading the dataset, preprocessing it, created the model and found out the predictions using the model. During preprocessing we found that this dataset has 43 classes. Model reached an accuracy of 95%+ in just 50 epochs, we can further optimize the model using hyper parameter tuning and reach a higher accuracy. 
