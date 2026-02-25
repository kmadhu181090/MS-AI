All the deliverables for this project can be found in the below links:

Github Link:

https://github.com/kmadhu181090/MS-AI/tree/542d7fe5d59129ede2200e924c1cd4b2bb52ec28/Pathway%20Machine%20Learning%3A%20Theory%20%26%20Hands-On%20Practice%20with%20Python%20Specialization/CSCA%205642%3A%20Introduction%20to%20Deep%20Learning

Video Link:

[Watch: Deep Learning: A Visual Introduction](https://www.youtube.com/watch?v=k-8KcPKCzsY)

Data Source Link: https://ai.stanford.edu/~amaas/data/sentiment/

Can also be downloaded from https://drive.google.com/file/d/1X8oOLAHrCgpaFEgNOOkJ-eGrz4BgvQNC/view?usp=drive_link

Project Steps:

1.Project Description and Objective
2.Citation
3.Data Loading
4.Exploratory Data Analysis
5.Data Cleaning and Preprocessing
6.Model Building and Interpretation
--Baseline
--BiLSTM (Standard)
--BiLSTM(Tuned)
--1D CNN (Standard)
--1D CNN (Tuned)
--GRU (Standard)
--GRU (Tuned)
7.Model Summary
8.Conclusion
9.Improvements
10.Challenges
11.References

Project Description and Objective
Project Description:

This project uses the IMDB Large Movie Review dataset, which contains 25,000 labelled movie reviews for training and 25,000 labelled movie reviews 
for testing. It's a binary sentiment classification problem where the goal is to classify the IMDB reviews as positive or negative.

Project Objective:

The main objective of the project is to build and evaluate deep learning models to classify whether the IMDB review is positive or negative. 
I have used the following deep learning models to classify the sentiment of a review. I have chosen the best model based on the accuracy, 
loss values, and F1 score, and implemented the best model on the test set. Hyperparameter tuning(using Keras Tuner) was performed for BiLSTM, CNN, 
and GRU models.

Models Implemented:

Baseline Model
BiLSTM (Standard)
BiLSTM Tuned
CNN (Standard)
CNN Tuned
GRU (Standard)
GRU Tuned
Data Description:

This dataset has reviews and a label (0 or 1 ) to indicate if they are positive or negative.

0-Negative 1-Positive

Dataset Size:

25000 reviews - Training 25000 reviews - Testing

From the training set, I created a validation split.

20000 for training 5000 for validation.

Each review is in a separate .txt file. The train folder has 2 separate folders. One each for positive and negative reviews. Similarly, the 
test folder has 2 separate folders, one for positive and negative reviews.

aclImdb - aclImdb_v1.tar.gz (zip) (82 MB) train/pos/12500.....train/neg/12500 test/pos/12500.....test/neg/12500

Citation:
Data Source Link: https://ai.stanford.edu/~amaas/data/sentiment/

1.Data Source for this project can be found in the below link:
Sentiment Analysis. (n.d.). Ai.stanford.edu. https://ai.stanford.edu/~amaas/data/sentiment/

‌2. Maas, A. L., Daly, R. E., Pham, P. T., Huang, D., Ng, A. Y., & Potts, C. (2011, June 1). Learning Word Vectors for Sentiment Analysis. Association for Computational Linguistics. https://ai.stanford.edu/~amaas/papers/wvSent_acl2011.bib

‌3.@InProceedings{maas-EtAl:2011:ACL-HLT2011, author = {Maas, Andrew L. and Daly, Raymond E. and Pham, Peter T. and Huang, Dan and Ng, Andrew Y. and Potts, Christopher}, title = {Learning Word Vectors for Sentiment Analysis}, booktitle = {Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies}, month = {June}, year = {2011}, address = {Portland, Oregon, USA}, publisher = {Association for Computational Linguistics}, pages = {142--150}, url = {http://www.aclweb.org/anthology/P11-1015} }
