# Date-Conversion

## What

In this repository, I achieve a very easy task of date conversion using complex Encoder-Decoder models with various approaches. The following conversion was to be achieved, `"%B %d, %Y"` to `"%Y-%m-%d"`. For example, "Februray 07, 2001" to "2001-02-07". 

## Why

Though there are certainly much easier ways to convert dates (e.g., using regular expressions or even basic string manipulation), I wanted to test the capabilities and intrinsic complexities of different Encoder-Decoder models and techinques in terms of accuracy and time taken for training. I also wanted to experiment with the different APIs provided by Tensorflow to create neural networks.

## How

The following techniques were used:

- Sequential API
  1. A basic seq2seq model
- Functional API
  1. Teacher Forcing
  2. TF-Addons's seq2seq with
      1. Training Sampler (training) + Decoder (inference)
      2. Training Sampler (training) + Greedy Embedding Sampler (inference)
      3. Scheduled Sampler (training) + Scheduled Embedding Sampler (inference)
