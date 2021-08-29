# Emojify

## Coursera - RNN Programming Assignment

### Disclaimer:
The given solutions in this project are only for reference purpose.

### Description of experiment

Welcome! We're going to use word vector representations to build an Emojifier. 🤩 💫 🔥

Have you ever wanted to make your text messages more expressive? Your emojifier app will help you do that. Rather than writing:

"Congratulations on the promotion! Let's get coffee and talk. Love you!"

The emojifier can automatically turn this into:

"Congratulations on the promotion! 👍 Let's get coffee and talk. ☕️ Love you! ❤️"

We'll implement a model which inputs a sentence (such as "Let's go see the baseball game tonight!") and finds the most appropriate emoji to be used with this sentence (⚾️).

## Using Word Vectors to Improve Emoji Lookups

1. In many emoji interfaces, we need to remember that ❤️ is the "heart" symbol rather than the "love" symbol. <br>
2. In other words, we'll have to remember to type "heart" to find the desired emoji, and typing "love" won't bring up that symbol. <br>
3. We can make a more flexible emoji interface by using word vectors! <br>
4. When using word vectors, we'll see that even if your training set explicitly relates only a few words to a particular emoji, our algorithm will be able to generalize and associate additional words in the test set to the same emoji. <br>
5. This works even if those additional words don't even appear in the training set. <br>
6. This allows us to build an accurate classifier mapping from sentences to emojis, even using a small training set. <br>

## What we'll build:

1. In this exercise, we'll start with a baseline model (Emojifier-V1) using word embeddings. <br>
2. Then we will build a more sophisticated model (Emojifier-V2) that further incorporates an LSTM. <br>

By the end of this notebook, you'll be able to:
<br>
1. Create an embedding layer in Keras with pre-trained word vectors <br>
2. Explain the advantages and disadvantages of the GloVe algorithm <br>
3. Describe how negative sampling learns word vectors more efficiently than other methods <br>
4. Build a sentiment classifier using word embeddings <br>
5. Build and train a more sophisticated classifier using an LSTM <br>

🏀 👑

👆 😎

(^^^ Emoji for "skills")

### Acknowledgements

https://www.coursera.org/learn/nlp-sequence-models <br>
https://www.deeplearning.ai/program/deep-learning-specialization/
