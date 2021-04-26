# Date-Conversion
In this repo, I achieve a very easy task of date conversion using an Encoder-Decoder model with various approaches. The following example conversion was to be achieved "April 22, 2019" to "2019-04-22".   
The following approaches were used:
- a very basic seq2seq model
- feeding the shifted targets to the decoder (teacher forcing)
- using TF-Addons's seq2seq implementation
  - normal
  - with scheduled sampler
  - with attention mechanism
