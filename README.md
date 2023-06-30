# Textual Pattern Analysis with Unigram and Bigram Models

This Python project aims to perform language processing on a given piece of text, focusing on identifying and analyzing unigrams and bigrams within the text. It also assesses the likelihood of occurrence for a randomly generated string of words based on the computed bigram model.

## Dependencies

This project is written in Python and uses the following libraries:

- `nltk`
- `random`
- `pandas`

Ensure that you have these libraries installed in your environment before running the code.

## How to Run

This project is a standalone Python script and does not require any arguments to run. Simply navigate to the directory containing the script and run it.

## Description of the Code

The code starts by importing the necessary libraries and setting up the input paragraph. It then tokenizes this paragraph into words using the `nltk.word_tokenize()` function.

The script calculates unigrams (individual words) and bigrams (pairs of consecutive words) from the tokens using the `ngrams` function from the `nltk.util` module.

These unigrams and bigrams are then converted into pandas DataFrames for a clean and clear display. All rows and columns are displayed without limitation by changing pandas' display options.

The last part of the script generates a random string of words whose length is less than 5. It then calculates the probability of the occurrence of this random string in the input paragraph based on the bigram model. This calculation is done by dividing the frequency of each bigram in the random string by the total number of bigrams. If the random string has a probability of 0 or 1, it regenerates the string until a suitable one is found.

The script finally prints the generated random string and its calculated probability.

## Output

The code will output two tables, one showing the unigrams and the other showing the bigrams. Then, it will output the randomly generated string and its probability of occurrence based on the bigram model.
