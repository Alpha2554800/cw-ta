NLP Report: Climate Sentiment & Named Entity Recognition - 
This repository contains the code and report for a series of natural language processing (NLP) tasks, focusing on sentiment analysis and named entity recognition.

Task 1: Climate Sentiment Analysis
This task explores and compares different machine learning models for classifying climate-related text.

Methods- 
Naïve Bayes Classifier: A simple yet effective probabilistic model. We applied several preprocessing techniques, including lemmatization, stopword removal, and combined unigram and bigram feature extraction, to significantly improve its performance.

Feedforward Neural Network (FFNN): A basic neural network was used to classify the text.

BERT-tiny: A small version of the BERT transformer model was fine-tuned for this classification task.

Key Findings- 
The improved Naïve Bayes classifier performed the best, achieving an accuracy of 79.5%.

This demonstrates that with strategic preprocessing and feature engineering, conventional models can outperform more complex neural networks, especially when the latter are constrained by architecture or hyperparameter choices.

Task 2: Topic Analysis- 
This section of the report uses an unsupervised learning approach to identify key themes in climate-related risks and opportunities.

Method- 
Latent Dirichlet Allocation (LDA): This model was used to discover topics in the text data without predefined categories. We compared a basic model with unigrams against an advanced model incorporating bigrams.

Key Findings- 
The advanced LDA model with bigrams provided a more detailed and accurate view of the topics.

The analysis successfully distinguished between risk topics (e.g., financial exposures, policy changes) and opportunity topics (e.g., renewable energy, green finance).

Task 3: Named Entity Recognition (NER) on Twitter -
This task focuses on identifying and classifying named entities (e.g., persons, organizations, locations) within informal Twitter text.

Method- 
Fine-tuned BERT-based Model: A pre-trained BERT model was fine-tuned for the specific task of token classification on social media data. We addressed the challenge of WordPiece tokenization to ensure accurate label alignment.

Key Findings- 
The model achieved high performance, with an F1-score of 0.88 for identifying persons (PER).

This highlights the effectiveness of BERT's contextual understanding and sub-word tokenization for handling the unique challenges of informal language on platforms like Twitter.

Authorship :
This project was done by Alpha Anindita
