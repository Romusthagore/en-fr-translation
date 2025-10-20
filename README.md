# English → French Translation Notebook

This repository contains a Colab notebook for English to French translation using the pre-trained MarianMT model from Hugging Face Transformers. No fine-tuning is included; the model is loaded directly from Hugging Face.

## Requirements

Install the dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

Open the notebook in Google Colab and run the cells. The notebook demonstrates:

- Loading the MarianMT EN→FR model
- Translating individual sentences or paragraphs
- Measuring translation speed and quality using BLEU and chrF scores
- Bidirectional translation (FR→EN) for testing

