
# Phishing Website Detection Using Machine Learning





## Objective

To develop a robust machine learning model capable of accurately identifying phishing websites, safeguarding users from fraudulent activities and financial losses by detecting malicious URLs and suspicious content.
## Data Used
PhishTank: A real-time updated database (CSV, JSON) of phishing URLs is utilized for training data. We extract 5,000 random phishing URLs from this valuable resource. (https://phishtank.org/)

University of New Brunswick: Their publicly available dataset 
(https://www.unb.ca/cic/datasets/url-2016.html) provides a rich collection of URLs. From this, we specifically target the "benign" category, extracting 5,000 random legitimate URLs to train our models alongside the phishing data.
## Models Used 
To train and evaluate our machine learning models, we split the collected dataset into two subsets: 80% for training (8,000 samples) and 20% for testing (2,000 samples). The problem of classifying URLs as phishing or legitimate is a typical supervised machine learning classification task.

We experiment with several established classification algorithms: Decision Trees, Random Forests, Multilayer Perceptrons, XGBoost, Autoencoders, and Support Vector Machines. Each model is trained on the training dataset and subsequently evaluated using the held-out test set to assess its performance in accurately identifying phishing websites.

## Demo
For Demo and more information check- https://colab.research.google.com/drive/1wqpNSVRAYA8t-5Lwm9072WrI_EFJykBk?usp=sharing


