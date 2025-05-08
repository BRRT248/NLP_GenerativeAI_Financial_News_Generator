# NLP / Generative AI – Financial News Generator

This project uses a pretrained GPT-2 language model (`distilgpt2`) to generate synthetic financial news headlines from user-provided prompts. It demonstrates how generative AI can be applied to content creation in finance.

## Dataset

A small file of sample financial news headlines (`financial_headlines.txt`) was prepared for prompt inspiration. No fine-tuning was performed; the model was used as pretrained.

## Workflow

- Loaded a pretrained GPT-2 (`distilgpt2`) model from HuggingFace Transformers
- Provided prompts like `"Stock market reacts to"`
- Generated multiple synthetic news headlines
- Displayed generated outputs in a Jupyter Notebook

## Example Generated Headlines

