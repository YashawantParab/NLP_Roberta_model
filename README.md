# NLP_Roberta_model

### Roberta-base model: Robustly Optimized BERT Pre-training Approach

To decipher sequence-to-sequence attention from the sentence; transformers help to handle long-range dependencies with simplicity. Roberta transformers pre-trained model used from hugging Face and trained model with 20000 subsamples from the dataset.

Having the Encoder stack of transformers architecture as BERT, Roberta has an optimized approach for the best prediction matrix. It uses a byte-level BPE (Byte Pair Encoding) as a tokenizer and uses much larger mini-batches for training which improves the perplexity of masked language modeling objectives.
Used the basic NLP technique transformers Tokenizer that provides the input ids to train the Roberta model.
Attention mask module from transformers has features of repeating the computation multiple times in parallel which makes the model learn effectively.   

To train the model we need to modify each epoch’s weights and minimize the loss function. (AdamW Adaptive optimizer is among the best optimizer algorithm derived from the adaptive moment Estimation mechanism.) 
