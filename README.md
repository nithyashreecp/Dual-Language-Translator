# Dual Language Translator

## Problem Statement
This project implements a Dual Language Translator using deep learning and Hugging Face Transformers. 
It was developed as a training project and extended with internship-level tasks such as GUI integration, 
preprocessing, and reproducibility improvements.

## Dataset
- Custom dataset or publicly available bilingual corpus (user must specify/replace with actual source).
- Preprocessing includes tokenization and preparation for seq2seq translation.

## Methodology
1. Install required libraries (transformers, torch, gradio, pandas, etc.).
2. Load and preprocess dataset (tokenization, cleaning).
3. Train translation model (baseline and improved).
4. Evaluate translations using BLEU or other metrics.
5. Develop Gradio GUI for interactive translations.
6. Save model for reuse.

## Features
- Hugging Face Transformers for sequence-to-sequence modeling
- Preprocessing pipeline for bilingual text
- Interactive Gradio-based GUI for translations
- Modular design for reproducibility and extension

## Results
- Translation model trained and tested successfully.
- GUI demo allows bilingual text translation.
- Further work: evaluation with BLEU, saving models, attention visualization.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook Dual_Language_Translator.ipynb
```

Or run the Gradio app cell inside the notebook to launch the translator.

## Reproducibility
- Requirements provided in `requirements.txt`
- Notebook includes installation cells
- Add dataset instructions before submission

## Internship Extension
- Added GUI using Gradio
- Added preprocessing pipeline
- Organized project for reproducibility
- Checklist created for missing items (BLEU evaluation, plots, dataset clarity, model saving)
