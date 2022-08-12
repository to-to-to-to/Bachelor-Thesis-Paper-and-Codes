# About The Project

This Is my Bachelor Thesis Project under the supervision of Reza Fuad Rachmadi, Ph.D. The Project Namely 
"Indonesian Twitter Emotion text Detection using BERT" is about How **Bidirectional Encoder Representations From Transformers (BERT)** Works in Text Classification Task.
The Dataset that I used is [Indonesian Twitter Emotion Dataset](https://github.com/meisaputri21/Indonesian-Twitter-Emotion-Dataset) that Contains 4403 Indonesian tweets which are labeled into five emotion classes: love, anger, sadness, joy and fear.

I Conducted some types of Tests and Parameters and tuned up the model and got the highest result in **90%** accuracy score.

# BERT In a Nutshell

**Bidirectional Encoder Representations from Transformers (BERT)** is a transformer-based machine learning technique for natural language processing (NLP) pre-training developed by Google. BERT was created and published in 2018 by Jacob Devlin and his colleagues from Google. 

<p align="center">
  <img src="https://miro.medium.com/max/1400/0*m_kXt3uqZH9e7H4w.png"/>
</p>

BERT makes use of Transformer, an attention mechanism that learns contextual relations between words (or sub-words) in a text. In its vanilla form, Transformer includes two separate mechanisms — an encoder that reads the text input and a decoder that produces a prediction for the task. Since BERT’s goal is to generate a language model, only the encoder mechanism is necessary. The detailed workings of Transformer are described in a paper by Google.

As opposed to directional models, which read the text input sequentially (left-to-right or right-to-left), the Transformer encoder reads the entire sequence of words at once. Therefore it is considered bidirectional, though it would be more accurate to say that it’s non-directional. This characteristic allows the model to learn the context of a word based on all of its surroundings (left and right of the word).


# How to Read My Project through this Repo

- [Paper](https://github.com/to-to-to-to/Bachelor-Thesis-Paper-and-Codes/blob/master/paper.pdf)
- [Codes](https://github.com/to-to-to-to/Bachelor-Thesis-Paper-and-Codes/tree/master/Codes)

