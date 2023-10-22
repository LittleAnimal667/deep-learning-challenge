# deep-learning-challenge

Alphabet Soup, a non-profit organization, is seeking a predictive tool to assist in selecting funding applicants with the highest likelihood of achieving success in their endeavors. Leveraging expertise in machine learning and neural networks, I will utilize the dataset's features to build a model whose purpose is to predict whether applicants will achieve success upon receiving funding from Alphabet Soup.

I have been provided with a CSV file by Alphabet Soup's business team, which encompasses data on over 34,000 organizations that have previously received financial support from the organization. 


To achieve this I will first preprocess the data to prepare for model development:

* Read the csv into a Pandas dataframe identifying the target and feature variables.

* Use "pd.get_dummies()" to encode categorical variables.

* Split the preprocessed data into feature array (X) and target array (y).

* Apply the "train_test_split" function for data division.

* Scale the training and testing feature datasets using StandardScaler.


After the data preprocessing is complete, I will design, train, and optimize a binary classification model using TensorFlow:

* Create a neural network model using TensorFlow and Keras, then inspect the model structure.

* Compile the neural network model and set up the training regimen.

* Evaluate the model's performance using the test data, calculating loss and accuracy.

The final aim is to achieve a predictive accuracy higher than 75% by adjusting the model and dataset by adjusting model architecture, such as the number of neurons and layers, and experimentation with activation functions as well as fine-tuning training parameters, like the number of training epochs.