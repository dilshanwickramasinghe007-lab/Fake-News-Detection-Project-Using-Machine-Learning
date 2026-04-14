#Fake News Detection System (Machine Learning)

This project is a hands-on implementation of a Fake News Detection System using Python and multiple machine learning algorithms. It follows a complete data science pipeline from data preprocessing to model evaluation to classify news articles as fake or real.

Project Overview:

The system analyzes textual news data and predicts whether a given article is fake or genuine. It leverages natural language processing (NLP) techniques and compares multiple machine learning models to achieve accurate predictions.

Key Features:
Data collection and labeling of fake & real news datasets
Text cleaning using Regular Expressions (regex)
Feature extraction using TF-IDF Vectorization
Training multiple classification models
Performance comparison using evaluation metrics
Manual testing with custom user input

How It Works:
Data Collection & Preparation
Import fake and real news datasets
Label data (0 = Fake, 1 = Real)
Merge, shuffle, and clean unnecessary columns
Data Preprocessing
Remove URLs, HTML tags, punctuation, and digits
Convert text to lowercase for consistency
Feature Extraction
Transform text into numerical vectors using TF-IDF
Model Training & Evaluation
The following models are trained and compared:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Gradient Boosting Classifier
Manual Testing
Input custom news text
Model predicts whether it is Fake or Real

Example:
Input: Custom news article text
Output: Prediction → Fake or Real

Technologies Used:
Python
Pandas
NumPy
Scikit-learn
Regex (re)

Future Improvements:
Deploy as a web application (Streamlit / Flask)
Use deep learning models (LSTM, BERT)
Improve accuracy with larger datasets
Add real-time news API integration
