# Hierarchical-Clustering-for-Seed-Categorization
CSE-6363-001-MACHINE LEARNING: Final Project: Clustering on the UCI seed dataset to divide it in groups and use the cluser IDs as labels for a subsequent K nearest neighbor classifier to identify the species. Technologies used: Python, Machine Learning Algorithms, Data Science, Jupyter Notebook

Problem Statement: Implement Hierarchical Clustering on the UCI seed dataset to divide it in groups and use the cluser IDs as labels for a subsequent K nearest neighbor classifier to identify the species. You should use multiple clusterings here and have to determine what a good number of clusters would be and how to determine the similarity between clusters and a data point.

Hierarchical Clustering for Seed Categorization Project:

1. Dataset: The dataset used in this study is publicly available on the UCI website 
(http://archive.ics.uci.edu/ml/datasets/seeds)

3. I have downloaded the dataset from the above link and divided the dataset into training and test 
dataset in 70:30 ration respectively.
* The training dataset is in the file seeddataset.csv.
* The testing dataset is in the file seeddatasettest.csv.

4. The implementation of the project is in the file ML_Final_Project.ipynb .
   
Instruction to run the code:
Google Colab was used as the execution environment. To ensure that the 
dataset is accessible to the code, it needs to be uploaded to Google Drive and its path should be specified 
in the code. Once the dataset is uploaded and the path is specified, the user can run all the cells in the code 
to see the output for each cell.

Steps to run the code:
1. Open google cobal.
2. Upload the .csv data files respectively.
3. The dataset files are in .csv files: seeddataset.csv and seeddatasettest.csv.
4. Please place the path of the file in read_csv line respectively of the first cell in 
ML_Final_Project.ipynb.
for example: pd.read_csv('/content/drive/MyDrive/ML/seeddataset.csv',dtype='object')
5. Select "Runtime" on top menu and choose "Run all" to run all cells.
6. The output is seen respectively.
7. Comparison answers for required questions are written in the text cell
