# Plant Leaf Disease Prediction using Machine Learning 
Check out the site here: Deployed App
# About:
In this project, I will discuss how to create a convolutional neural network which will predict whether a plant is suffering from a disease or not. 
Different layers and other hyperparameters are used for building, training, validating and testing CNN classification model. 
TensorFlow and Keras are used to implement this project. 
 # Motivation:
1. There is a need to increase food production by an estimate of 70% by 2050 to feed an expected population size that is predicted to be over 9 billion people. 
2. Currently, infectious diseases reduce the potential yield by an average of 40%.
3. Many farmers in the developing world experiencing yield losses as high as 100%.
   
    # Steps to implement the Plant Leaf Disease Prediction project
1. Mount the google drive on Google Collab Notebook and import the data set
2. Import the required libraires
3. Visualizing the images and Resize images
4. Convert the images into a NumPy array and normalize them. 
5. Visualize the class count and Check for class imbalance 
6. Splitting the dataset into train, validate and test sets
7. Performing one-hot encoding on target variable
8. Creating the model architecture, compile the model and then fit it using the training data
9. Plot the accuracy and loss against each epoch
10. Make predictions on testing data 
11. Visualizing the original and predicted labels for the test images
12. Deploy the project using Streamlit 

 # commands Used In Anaconda prompt:
pip install pipreqs

pipreqs

pip install -r requirements.txt

streamlit run main_app.py

 # Requirments of the project are:
keras==2.12.0

numpy==1.23.5

streamlit==1.22.0

opencv_python==4.6.0.66

tensorflow==2.12.0

