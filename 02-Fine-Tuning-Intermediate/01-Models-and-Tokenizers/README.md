# Models & Tokenizers Notebook

This Jupyter Notebook explores the usage of transformers library to interact with models and tokenizers.

## Installation

To run the notebook, make sure you have the `transformers` library installed. You can install it via pip:

```bash
pip install transformers
```

The notebook uses `bert-base-uncased` as the checkpoint for the examples. It demonstrates how to utilize the transformers' `AutoTokenizer` to preprocess text data and `AutoModelForSequenceClassification` to build a model for text classification.

## Tokenization

The notebook explores various tokenization tasks using the AutoTokenizer:

- Tokenizing text: Breaking down text into tokens.
- Converting tokens to IDs: Getting the token IDs from the tokenizer's vocabulary.
- Converting IDs to tokens: Reversing token IDs to tokens.
- Decoding IDs: Converting token IDs back to text.

## Model Interaction

The notebook illustrates how to use `AutoModelForSequenceClassification`:

- Initializing the model from a checkpoint.
- Generating model inputs for text.
- Extracting outputs from the model (logits).
- Running inference on a single text sequence and multiple text sequences.

## Execution

The notebook provides code examples with outputs showcasing the usage and interactions with both tokenizers and models.

## Dependencies

The main dependencies used in the notebook are:
- `transformers` library
- `AutoTokenizer` for tokenizing text data
- `AutoModelForSequenceClassification` for handling sequence classification tasks

## Note

For effective model training and fine-tuning, it's recommended to further train the initialized models on downstream tasks according to the specific requirements.

For more details, refer to the complete notebook "Models&Tokenizers.ipynb".
