# Date-Conversion
## What
In this repository, I achieve a very easy task of date conversion using complex Encoder-Decoder models with various approaches. The following conversion was to be achieved, `"%B %d, %Y"` to `"%Y-%m-%d"`. For example, "Februray 07, 2001" to "2001-02-07". 

## How
The following approaches were used:
- a basic seq2seq model
- teacher forcing
- using TF-Addons's seq2seq implementation
  - basic
  - with scheduled sampler
  - with attention mechanism
