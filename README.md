# Phishing-Website-Detection-using-ML
This project focuses on detecting phishing websites using Machine Learning techniques.
The system analyzes URL features, domain characteristics, and additional behavioral attributes to classify a website as Safe or Unsafe.
A trained ML model is integrated with a Flask-based web application, allowing users to check URLs in real time.

Machine Learning Workflow
1.	Dataset Collection
   o	Phishing + Legitimate website URLs
   o	Includes URL-based, domain-based, and behavior-based features
2.	Feature Extraction
   o	URL length
   o	Number of dots
   o	HTTPS presence
   o	IP address usage
   o	Subdomains count
   o	Prefix/suffix patterns
   o	Domain age (WHOIS)
3.	Data Preprocessing
   o	Handling missing values
   o	Encoding
   o	Scaling
   o	Train-test split
4.	Model Training (Jupyter Notebook)
   o	Logistic Regression
   o	Decision Tree
   o	Random Forest
   o	SVM
   o	KNN
5.	Model Evaluation
  o	Accuracy
  o	Precision, Recall, F1-score
  o	Confusion Matrix
  o	ROC curve
  o	Feature importance
6.	Model Deployment
   o	Flask backend loads the trained .pkl model
   o	Frontend built using HTML, CSS, and JavaScript
   o	User enters URL → system returns prediction instantly


Tech Stack Used
    Technology	          Purpose
Python                ML logic & backend
Jupyter Notebook	    Training and analysis 
Flask	                Web application backend
HTML	                Structure of UI
CSS	                  Styling and layout
JavaScript	          Frontend logic & API calls


