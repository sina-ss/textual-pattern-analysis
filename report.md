# Textual Pattern Analysis with Unigram and Bigram Models

## Introduction:

In this project we aims to perform a basic language processing task on a given piece of text, focusing on identifying and analyzing unigrams and bigrams within the text. Furthermore, it also assesses the likelihood of occurrence for a randomly generated string of words based on the computed bigram model.

The text selected for this project is a paragraph related to information retrieval and sentence embeddings in the context of AI programming.

**selected text:**

`One use of sentence embeddings is information retrieval. Consider the task of searching the Snap! manual or this AI programming guide. String matching cannot take into account synonyms, different ways of saying the same thing, or different spelling conventions. In this sample search project sentence embeddings are used to compare the user's query with sentence fragments from the manual and guide. By relying on the features closest to the list of features block the closest fragments are found very quickly. The embeddings of all the fragments have been pre-computed so only the embedding of the user's query is needed.`

## Methodology:

The project was conducted in three main stages:

1. **Text Processing**: The input paragraph was tokenized using NLTK's `word_tokenize` function, breaking it down into a list of individual words (tokens).
2. **Unigram and Bigram Calculation**: Lists of unigrams and bigrams were generated. Unigrams represent individual words, while bigrams represent pairs of consecutive words in the text.
3. **Random String Generation and Probability Calculation**: A string of less than 5 words was randomly generated from the unigram list, and its probability of occurrence in the paragraph was calculated based on the bigram model.

## Results:

The lists of unigrams and bigrams offer insight into the distribution and sequencing of words in the paragraph. By reviewing these lists, one can identify common word pairs (bigrams), which can hint at the underlying patterns or themes in the text.

The randomly generated string of words, and its associated probability of occurrence according to the bigram model, provides an interesting demonstration of how language models can predict the likelihood of certain phrases appearing in a given text.

## Conclusion:

Through this project, we were able to dissect a paragraph into its constituent unigrams and bigrams and compute the probability of occurrence for a randomly generated phrase based on these constructs. This exercise provided an introductory look into the realm of Natural Language Processing (NLP) and showcased the potential applications of NLP in tasks such as information retrieval, text summarization, and sentiment analysis.

The methods used in this project, such as unigram and bigram analysis, are fundamental to more complex language modeling techniques like trigrams, n-grams, and even machine learning-based models for text analysis.

This project can serve as a springboard for more complex NLP projects, such as building language models, creating a recommendation engine, or designing an intelligent text processing system.
