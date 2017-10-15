# Artificial Neural Network - Using Back Propagation Algorithm

### Synopsis
The Backpropagation algorithm has been used to create the Artificial Neural Network in this project. Following are the features of this project - 
  - Preprocess the data before entering in to the Back-Propagation Algorithm. All the data are converted to numeric and then subtracting the mean of the attribute values followed by the division using the Standard Deviation. 
  - The Preprocessed file will be saved and Backpropagation Program will take it and create the neural network
  - The Program has 3 broad parts - 2 for creation (Forward Pass and Backward Pass) and 1 for Testing to get the errors and accuracy
  - We have used 3 different data Sets mentioned in the Question to train the network and test 

### Motivation

This project is done as a class assignment for CS6375 - Machine Learning. We have developed this code to get the real-world view of the Backpropagation Algorithm, which was studied in class before the assignment was given.

### Software’s Used
Following are the software’s used to develop this project - 
  - Python 3.6
  - IDE: PyCharm - Community Edition 2017.2

Following are the Python packages used in the code - 
  - panda
  - numpy
  - random
  - math
  - sys
  - logging
  - statistics

### How to Run the Code 

Following are the steps to run the code - 
  - Download the project folder - "ANN" and save in the local
  - Start PyCharm
  - Open the project folder selecting the saved project folder.
  - Preprocessing.py script needs 2 inputs from the user: 
    - Input File URL/ Path
    - Output File path
  - Run the Preprocessing.py file for Preprocessing and get the output in the desired path
  - Neural.py script needs 1 input from user
    - One Line will consist the below values separated by space 
      - input dataset – complete path of the post-processed input dataset
      - training percent – percentage of the dataset to be used for training
      - maximum iterations – Maximum number of iterations that your algorithm will run.
      - number of hidden layers
      - number of neurons in each hidden layer
  - Run the Neural.py and get the following outputs -
    - Error after each iteration
    - Updated Weights
    - Errors and Accuracies for training and Testing



### References
  - https://visualstudiomagazine.com/articles/2014/01/01/how-to-standardize-data-for-neuralnetworks.aspx
  - https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/
  - https://www.mimuw.edu.pl/~son/datamining/DM/4-preprocess.pdf
  - http://neuralnetworksanddeeplearning.com/chap2.html
  - http://www.statisticshowto.com/mean-squared-error/
  - https://en.wikipedia.org/wiki/Mean_squared_error
