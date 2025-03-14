Sentiment Analysis with NLTK and Transformers

Overview

This project performs sentiment analysis using both NLTK and Hugging Face's Transformers. Sentiment analysis is the process of determining whether a piece of text expresses a positive, negative, or neutral sentiment.

Technologies Used

Python

Installation

Clone the Repository:-
git clone https://github.com/SAMUDRAGUPTA002/sentiment-analysis.git
cd sentiment-analysis

Install Dependencies :-
Ensure you have Python 3.7 or later installed. Then, install the required libraries:

\pip install nltk transformers torch

NLTK (Natural Language Toolkit) :-
import nltk
from nltk.sentiment import SentimentIntensityAnalyzer

nltk.download('vader_lexicon')
sia = SentimentIntensityAnalyzer()

text = "I love this product! It works wonderfully."
score = sia.polarity_scores(text)
print(score)  # Output includes positive, negative, and neutral scores

Hugging Face Transformers :-
from transformers import pipeline

sentiment_pipeline = pipeline("sentiment-analysis")

text = "I love this product! It works wonderfully."
result = sentiment_pipeline(text)
print(result)  # Output includes label and confidence score

PyTorch

Pandas

Installation

Ensure you have Python installed (preferably 3.8+). Then, install the required dependencies using:

pip install nltk transformers torch pandas

Dataset

You can use any text dataset for sentiment analysis. For example, the Amazon Fine Food Reviews dataset or Twitter data.

License

This project is open-source under the MIT License.
