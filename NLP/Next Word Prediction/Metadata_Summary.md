# Next Word Prediction

## Assignment

You've certainly heard about the GPT language models that are used by many AI tools such as ChatGPT. What these models do, in simple terms, they try to accurately predict what the most logical next word would be given an input. In this project, you will try to implement a similar model, of course, much less advanced. Select a set of training data with a lot of real-life text (e.g. a book) and use it to train a neural network which, given input with a couple of words, returns the list of the most probable words that would make for a logical continuation.

#### Tips

Start by reading in the text data and splitting the long text into individual words;
Feel free to explore, analyze and describe the text using statistics such as you would do with any other dataset; look for the most and least frequently occurring words as well as common combinations of two consecutive words - you can use these findings for testing later;
For simplicity, let's select a set length of input X, e.g. 5 words; feel free to experiment with different lengths;
Iterate through all words from the dataset and for all possible sets of X consecutive words (input) note what is the word that comes next (output);
Encode the input and output words in form of Boolean arrays where each value corresponds to a unique word that appears in the original text; Don't forget to split the data into training, testing, and possibly, validation sets;
Train and evaluate a neural network using these input and output sets; Start with a simple model and experiment by adding and tuning layers;
Test the final model yourself by specifying a sentence with X words that doesn't necessarily exist in the source text and observe which words will the model suggest as logical continuations;

## Data Description

The file book.txt contains the entire eBook 'The Adventures of Sherlock Holmes' by Arthur Conan Doyle in Plain Text (UTF-8) format. This eBook is for the use of anyone anywhere at no cost and with almost no restrictions whatsoever under the terms of the Project Gutenberg License (https://www.gutenberg.org/).

However, you can use any other long text or book as input for this project.
