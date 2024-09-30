
# Project Name: Comparative analysis of question classification techniques

This project performs binary classification on two different datasets: the Quora dataset and the Stack Overflow dataset. The objective is to classify questions as either sincere or insincere (Quora dataset) and open or closed (Stack Overflow dataset). The project implements four different models to achieve this: Logistic Regression combined with polynomial features, stacking classifier, BERT and XLM-R.
## Datasets

### Quora Dataset
The Quora dataset contains questions from Quora that are labeled as either sincere or insincere. You can download the dataset from Kaggle using the following link:
- [Quora Insincere Questions Classification](https://www.kaggle.com/c/quora-insincere-questions-classification/data). 
Download the train.csv file from the above link.

### Stack Overflow Dataset
The Stack Overflow dataset contains questions from Stack Overflow that are labeled as either open or closed. You can download the dataset from Kaggle using the following link:
- [Stack Overflow Question Classification](https://www.kaggle.com/c/predict-closed-questions-on-stack-overflow/data)
Download the train-sample.csv file from the above link.

## Uploading the Data
There are 2 seperate python files provided: 
1. Analysis_on_StackOverflow.ipynb: This conatins the implementation of the four mentioned models on stackoverflow dataset. To run the code for this file upload it on google colab further upload the train-sample.csv file (downloaded from Kaggle) on Colab.
2. Analysis_on_Quora.ipynb: This contains the implementation of the four model. Upload the file on colab along with the train.csv dataset to run the code.


