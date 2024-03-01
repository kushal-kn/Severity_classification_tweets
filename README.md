# Cyberbullying Severity Classifier
This project is a cyberbullying severity classifier that utilizes natural language processing (NLP) techniques and machine learning to classify the severity of cyberbullying tweets into three categories: Low, Medium, and High.

## Features
1. Performs sentiment analysis using TextBlob to assess the sentiment polarity of tweets.
2. Utilizes spaCy for tokenization and lemmatization of tweet text.
3. Implements custom rules based on keyword detection and sentiment polarity for severity classification.
4. Constructs a deep learning model using TensorFlow and Keras for automated severity classification.
5. Provides visualization of model training history and evaluation metrics.
   
## Prerequisites
To run this project, you need Python installed on your system along with the following libraries:

1. pandas
2. spacy
3. scikit-learn
4. tensorflow
5. keras
6. textblob
   
Additionally, you need to download the spaCy English model by running the following command:

***python -m spacy download en_core_web_sm***

## Getting Started
1. Clone this repository to your local machine.
2. Install the required Python libraries mentioned in the requirements.txt file.
3. Download and install spaCy and the English language model.
4. Run the cyberbullying_classifier.ipynb notebook or execute the Python script cyberbullying_classifier.py.
5. Follow the prompts to classify the severity of cyberbullying tweets.
   
## File Description
* cyberbullying_classifier.ipynb: Jupyter Notebook containing the Python code for the cyberbullying severity classifier.
* cyberbullying_tweets.csv: CSV file containing cyberbullying tweets data.
* README.md: This README file providing an overview of the project.
