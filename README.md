# Date-Conversion
## What
In this repository, I achieve a very easy task of date conversion using complex Encoder-Decoder models with various approaches. The following conversion was to be achieved, `"%B %d, %Y"` to `"%Y-%m-%d"`. For example, "Februray 07, 2001" to "2001-02-07". 

## Why
Though there are certainly much easier ways to convert dates (e.g., using regular expressions or even basic string manipulation), I wanted to test the capabilities and intrinsic complexities of different Encoder-Decoder models and techinques in terms of accuracy and time taken for training.

## How
The following techniques were used:
- A basic seq2seq model
- Teacher Forcing
- TF-Addons's seq2seq implementation
  - Vanilla
  - with Scheduled Sampler
  - with Attention Mechanism
