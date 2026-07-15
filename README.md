# Dialogue Summarization Demo

This project explores dialogue summarization using a Hugging Face `transformers` model inside a Jupyter notebook.

## Project Contents

- `DialogueSummarization.ipynb` — notebook demonstrating dataset loading, model inference, prompt engineering, and example summaries.

## What it does

The notebook:

1. Loads the `knkarthick/dialogsum` dataset from Hugging Face.
2. Uses `google/flan-t5-base` for sequence-to-sequence generation.
3. Compares baseline human summaries with generated model outputs.
4. Shows zero-shot, one-shot, and few-shot prompt techniques.

## Setup

Recommended Python packages:

- `datasets`
- `transformers`
- `torch`
- `jupyter`

Install them with pip:

```bash
pip install datasets transformers torch jupyter
```

If you use conda, create an environment first:

```bash
conda create -n dialogue-sum python=3.11
conda activate dialogue-sum
pip install datasets transformers torch jupyter
```

## Run the notebook

Open the notebook in Jupyter or VS Code and run the cells.

```bash
jupyter notebook DialogueSummarization.ipynb
```

## Notes

- The notebook is configured to ignore warnings.
- It uses the `google/flan-t5-base` model for text generation.
- The dataset examples are drawn from the `test` split of `knkarthick/dialogsum`.
