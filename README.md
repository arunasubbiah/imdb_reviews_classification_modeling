# Capstone Project 2
# IMDB Dataset - Classification Models Comparison

Binary sentiment classification is analyzing customers opinion such as online reviews or survey responses as positive or negative. It helps to understand how well a product or service is doing in the market and helps stakeholders to take swift action based on the analysis.  

**Purpose**  
In this project we will analyze movie reviews from IMDB and classify them into positive or negative using various Classification models and compare their performances.

**Dataset**
Training and testing dataset is taken from https://ai.stanford.edu/~amaas/data/sentiment/. This dataset contains movie reviews along with their associated binary sentiment polarity labels that serves as a benchmark for sentiment classification. There are totally 50,000 reviews split evenly into 25k train and 25k test sets with balanced distribution of labels (12500 positive and 12500 negative reviews in each set). Please go through the readme file provided in the link for more details. 

**Approach**
After the initial data wrangling and EDA (covered in Milestone 1), there are 3 major sections to the project. 
1. Classification Model Comparison  
Six classification models Logistic Regression, Naïve Bayes, SVM, Decision Tree, Random Forest, Light GBM are compared based on metrics such as, Accuracy, ROC_AUC, F1 score, Recall & Precision. Refer to Project_Report.pdf for metrics and plots used to compare the models.  

2. Feature Selection   
feature_importances_ attribute, RFE & PCA techniques are used to remove features that are not that significant and still have similar or better performance in much shorter training time.

3. Handling Class Imbalance   
class_weights parameter of sklearn's Logistic Regression, Resampling methods & SMOTE are analysed to handle class imbalance.


**Citations**  
• Maas, Andrew L. and Daly, Raymond E. and Pham, Peter T. and Huang, Dan and Ng, Andrew Y. and Potts, Christopher - Learning Word Vectors for Sentiment Analysis  


 





