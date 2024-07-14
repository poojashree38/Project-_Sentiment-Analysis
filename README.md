Sentiment Analysis of Reviews Deployment

Overview:

This project involves building a sentiment analysis model that classifies user reviews into positive, neutral, and negative sentiments. 
The model is trained using a dataset of reviews and various machine learning techniques. 
The project is implemented using Python and incorporates Natural Language Processing (NLP) techniques, machine learning algorithms, and a deployment interface using Streamlit.

Features:

Data Preprocessing: Includes steps for cleaning the text data, removing duplicates, and handling missing values.

Sentiment Analysis: Utilizes the VADER Sentiment Analyzer to label reviews as Positive, Negative, or Neutral.

Machine Learning Model: Trains a Random Forest classifier to predict sentiment based on TF-IDF vectorized text data.

Imbalanced Data Handling: Uses SMOTE to handle class imbalance in the training dataset.

Deployment: Deploys the sentiment analysis model using a Streamlit web application, allowing users to input text and get sentiment predictions.

Libraries and Tools

Pandas: For data manipulation and analysis

NumPy: For numerical computations

NLTK: For text preprocessing and lemmatization

VADER Sentiment Analyzer: For sentiment scoring

Scikit-learn: For machine learning model training and evaluation

Imbalanced-learn: For handling imbalanced datasets

Streamlit: For deploying the model as a web application


Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any features, bug fixes, or improvements.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
