# Keyword-extraction-using-K-means-Clustering-and-KNN


# Aim
This project intends to develop a method for keyword extraction based on word co occurrence and semantic correlations.

# Objective
  To classify the documents based on frequency of words. 
● To evaluate the performance of the proposed model by K-Means clustering and K nearest neighbour algorithms by calculating Accuracy, F1-Measure, Recall, and Precision. 
● To compare the performance of the proposed model with existing methods in the current context. 

# Methodology

In this methodology, we propose a technique for keyword extraction. First step is converting the collected dataset into structured data from unstructured text format and the second step includes the dataset preprocessing which includes the stop words removal,tokenisation,feature extraction using TF-IDF algorithm. Then after splitting the dataset into training and testing data by using the train_and_test module in python and applying K means clustering to reduce the polysemy problem which means missing the grouping of similar text. So, Clustering helped to group the similar kind of text and applied the K nearest neighbour algorithm to find the nearest keywords from the grouped keywords of structured content and top K keywords are extracted. Then to find the best way for extracting the keywords is to evaluate the parameters like Accuracy, Precision, Recall, F1-Score. The proposed method for extracting the keywords involves both supervised and unsupervised algorithms which are called semi-supervised algorithms. This model helps in finding the accurate keywords based on similarity between the words which helps to reduce the polysemy and easily find nearest words from the similar words that are grouped together. 

# Dataset

The dataset collected for the model of keyword extraction is from our academic subject related documents and converting the document into structured format means comma separated values and contains the matter related algorithms, artificial intelligence and also electrical department subjects like circuit engineering and many more. 

# Result

The proposed method which is which is the combination of K-means Clustering and K nearest neighbour algorithm gives the better results than exisiting method in terms of Accuracy,Precision, Recall, F-measure. The result of extraction of keywords is focused on extracting keywords based on semantic relationship and solves polysemy problem. 


