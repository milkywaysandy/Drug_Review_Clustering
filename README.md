# Drug_Review_Clustering

A unsupervised clustering machine leraning project on predicting drug user condition according to user review information.

**Project Backgound**
Patient's opion on the drug they are prescripted is very important because it directly influence the succeess of the treatment. Thus, with a clustering unsupervised learning model, I chose to use this Kaggle project to understand the relationship between the opion of the patient (compliance toward the drug) and the presciption.


**Dataset Information & Quick Result Recap**
This project is based on predicting condition of the drug user according to the dataset. 3 of the 7 columns in the dataset is in text format; thus, NLP technique, TF-IDF and word2vec, were used to successfully model building. Final model was build with Non-negative Matrix Factorization (NMF). The final accuracy is 0.86. In comparison, both kmean and Agglomerative Clustering were tested.


*Data Source:* The dataset is from kaggle; the information was gather from webscrapping of medicine review website. In the dataset, there are 7 features and 161297 records with no specific target.

[The Kaggle page to the dataset](https://www.kaggle.com/datasets/jessicali9530/kuc-hackathon-winter-2018/data).

Reference Journal Article: 
*Felix Gräßer, Surya Kallumadi, Hagen Malberg, and Sebastian Zaunseder. 2018. Aspect-Based Sentiment Analysis of Drug Reviews Applying Cross-Domain and Cross-Data Learning. In Proceedings of the 2018 International Conference on Digital Health (DH '18). ACM, New York, NY, USA, 121-125.*
