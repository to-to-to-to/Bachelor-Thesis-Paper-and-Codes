# About The Project

This Is my Bachelor Thesis Project under the supervision of Reza Fuad Rachmadi, Ph.D. The Project Namely 
"Indonesian Twitter Emotion text Detection using BERT" is about How **Bidirectional Encoder Representations From Transformers (BERT)** Works in Text Classification Task.
The Dataset that I used is [Indonesian Twitter Emotion Dataset](https://github.com/meisaputri21/Indonesian-Twitter-Emotion-Dataset) that Contains 4403 Indonesian tweets which are labeled into five emotion classes: love, anger, sadness, joy and fear.

I Conducted some types of Tests and Parameters and tuned up the model and got the highest result in **90%** accuracy score.

# BERT In a Nutshell

**Bidirectional Encoder Representations from Transformers (BERT)** is a transformer-based machine learning technique for natural language processing (NLP) pre-training developed by Google. BERT was created and published in 2018 by Jacob Devlin and his colleagues from Google. 

<p align="center">
  <img src="https://www.researchgate.net/publication/339786972/figure/fig3/AS:867018077118465@1583724626279/Architecture-of-the-BERT-based-discriminator-model-Raw-texts-are-fed-into-the-model-to.png"/>
</p>

BERT makes use of Transformer, an attention mechanism that learns contextual relations between words (or sub-words) in a text. In its vanilla form, Transformer includes two separate mechanisms — an encoder that reads the text input and a decoder that produces a prediction for the task. Since BERT’s goal is to generate a language model, only the encoder mechanism is necessary. The detailed workings of Transformer are described in a paper by Google.

As opposed to directional models, which read the text input sequentially (left-to-right or right-to-left), the Transformer encoder reads the entire sequence of words at once. Therefore it is considered bidirectional, though it would be more accurate to say that it’s non-directional. This characteristic allows the model to learn the context of a word based on all of its surroundings (left and right of the word).

The chart below is a high-level description of the Transformer encoder. The input is a sequence of tokens, which are first embedded into vectors and then processed in the neural network. The output is a sequence of vectors of size H, in which each vector corresponds to an input token with the same index.

When training language models, there is a challenge of defining a prediction goal. Many models predict the next word in a sequence (e.g. “The child came home from ___”), a directional approach which inherently limits context learning. To overcome this challenge, BERT uses two training strategies:
