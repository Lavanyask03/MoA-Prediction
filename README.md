# MoA-Prediction
Predicting the mechanism of action of drugs using Machine Learning

Mechanism of Action Prediction was a data science competition hosted on Kaggle by 
Laboratory for Innovation Science at Harvard.
The goal of the competition is advancing drug development through improvements to MoA prediction algorithms.

* **Data**: Gene expression data and cell viability data, compound or control perturbations, time and dosage of drugs along with the targets. 
* **Evaluation Function**: log loss.

Take a look at the competition data, rules and evaluation criteria :  [MoA Prediction](https://www.kaggle.com/c/lish-moa)

## Project contents:
1. Overview of the data, Exploratory Data Analysis and Principal Component Analysis of MoA Prediction : [MoA Prediction EDA](https://github.com/Lavanyask03/MoA-Prediction/blob/master/moa-prediction-eda.ipynb)
2. Training a simple neural network model to predict MoA : [MoA Neural Network](https://github.com/Lavanyask03/MoA-Prediction/blob/master/moa-prediction-neural-network.ipynb)
3. Improving the NN model with K fold cross validation : [MoA NN KFold CV](https://github.com/Lavanyask03/MoA-Prediction/blob/master/moa-prediction-nn-improved.ipynb)

## Run the code:
The code can be run in any of the following ways:
1. Run on Kaggle: The notebooks can be found on kaggle and can be directly run on kaggle by clicking the copy and edit button on the top right corner.
2. Run on Google Colab: The notebooks can be downloaded from github and run on Google Colab which has access to free cloud resources provided by Google.
3. Run on local machine: The code can be downloaded or you can also clone the repository. The notebooks can be run using jupyter-notebook on your local machine. Make sure that you have all the required libraries installed.

## Results:
* The simple NN model got a score of 0.02018 on public dataset and 0.01761 on private dataset.
* After KFold Cross validation, it could achieve a score of 0.01914 on public dataset and 0.01668 on private dataset.

## Personal experience:
This was the very frist time I participated in a live Data Science Competition and I did learn a lot of things on the way. Thanks to the Kaggle communtiy. Although I was just starting out in data science, I did manage to reach among the top 49% in the competition. I plan to participate in more competitions in the future.

## Kaggle notebook links:
1. [EDA](https://www.kaggle.com/lavanyask/moa-prediction-eda)
2. [NN](https://www.kaggle.com/lavanyask/moa-prediction-neural-network)
3. [KFold](https://www.kaggle.com/lavanyask/moa-prediction-nn-kfold)
