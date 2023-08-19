# Tensorflow-Student-Academic-Performance
👋 Welcome to my GitHub project!

## Purpose
The purpose of this project is to learn how to use libraries such as Tensorflow and Pytorch and similar in order to predict students' grades according to their sets of characteristics during an academic semester.</br>
For training and evaluation, the test data called [Student's Academic Performance](https://www.kaggle.com/datasets/aljarah/xAPI-Edu-Data) has been used.

## Description
1️⃣ Dataset Analysis:
- The dataset was imported and thoroughly examined.
- The number of data instances and the distribution among each class were analyzed.
- Non-numeric values were converted into numeric values to ensure proper data handling.

2️⃣ Dataset Split:
- The dataset was randomly divided into two parts: 80% for training and 20% for testing purposes

3️⃣ Model Implementation and Training:
- The models were designed and implemented using Tensorflow.
- For the initial case, a neural network was constructed with three intermediate layers using Dense or fully connected layers.
- The number of layers was gradually increased, and different architectures and hyperparameters were experimented with.
- Various activation functions, such as tanh, sigmoid, and ReLU, were explored to enhance the performance of the models.
- For the output layer, techniques like softmax or one-vs-all with sigmoid were considered.
- Throughout the model training process, graphs illustrating changes in accuracy and loss for each epoch were plotted to monitor overfitting.
- Techniques like Dropout and Batch Normalization were incorporated to assess their impact on accuracy and loss. It was ensured that Dropout and Batch Normalization were not used together.

4️⃣ K-fold Cross Validation and Model Selection:
- Among the developed models, the top three models based on their achieved accuracy were selected.
- These models were subjected to k-fold cross validation, specifically with k=5, to further validate their performance.
- Evaluation of the models using various performance metrics, including the Confusion Matrix, was performed.

Please refer to the code in the repository for a step-by-step guide on implementing the neural network, training the model, and evaluating its performance.
