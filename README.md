# SPACY-Hindi-NER-FASTEXT

# Creating a Hindi Named Entity Recognition (NER) Model Using SpaCy in a Jupyter Notebook

In this project, we'll walk you through building an NER model for the Hindi language using SpaCy. Our dataset is in the CoNLL format, but we'll show you how to convert it into SpaCy format for training and testing.

# Why Choose SpaCy?

We've chosen SpaCy because it's a well-established open-source library known for its production-level capabilities. One of its standout features is its customizable pipelines, which make NER tasks straightforward and efficient. Plus, it's known for its low latency, making it ideal for production environments.

# Getting Started

First, we'll need to obtain the Hindi dataset, which can be found at the provided Google Drive link. This dataset will serve as our foundation for building the NER model.

Now, let's dive into the Jupyter Notebook and the code to create a robust Hindi NER model using SpaCy.

Hindi Dataset (source above link) :- https://drive.google.com/file/d/1lXz5BEm7BUFBY_ETP-mGAxrBddCBL5_i/view?usp=sharing

# STEP
# Part 1: Data Preparation

Configure Colab for file uploads and load Hindi word vectors from FastText.
Convert training and testing data from CoNLL to SpaCy format.
Set up a SpaCy NER model for Hindi using FastText word vectors.
Showcase word similarity using the loaded vectors.

# Part 2: Model Training

Define essential functions to train and evaluate the SpaCy NER model for Hindi.
Train the model using custom training data for 100 iterations with dropout.
Evaluate the model's performance on test data and save the best model based on F1 score.
Provide functions for loading the trained model and scoring it.
Visualize NER results for both training and testing data.

# Part 3: Subset Training

Reuse the trained model and data for training and testing on different data subsets.
Retrain the model with 100 iterations on the new data subset.
Load the saved model and assess its performance on the test data.


