# Fake News Detection

## Overview
This project focuses on developing a machine learning model to accurately classify news as real or fake. Utilizing Python and various Natural Language Processing techniques, the model processes textual data to distinguish between authentic and misleading information.

## Features
- **Data Processing**: Implements techniques like lower casing, punctuation removal, and TF-IDF vectorization to transform raw text data into a format suitable for machine learning.
- **Machine Learning Model**: Employs a Logistic Regression model trained on a dataset containing over 44,000 news articles.
- **High Accuracy**: Achieves an accuracy of 98.47% in distinguishing between real and fake news, illustrating the model's efficiency.

## Technologies Used
- Python
- Pandas
- NLTK
- Scikit-learn

## Installation
To run this project, you will need Python installed on your machine. Clone this repository and install the required dependencies:

pip install pandas nltk scikit-learn

## Usage
Run the Jupyter Notebook to train the model and test its performance. The final section of the notebook includes a function `news_predictor` that can classify individual news snippets as real or fake.

## Dataset
The dataset comprises two CSV files: one containing real news and the other containing fake news. Each record is labeled accordingly.

## Contributions
This project is open for contributions. Feel free to fork the repository and submit pull requests.

