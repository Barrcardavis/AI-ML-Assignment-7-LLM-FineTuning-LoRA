# AI-ML-Assignment-7-LLM-FineTuning-LoRA

###Assignment 7 repository for LLM fine tuning

###By David Davis

####Base Model & Data set Used - roberta-base + imdb

####LoRA configuration summary (lora_r, lora_alpha, etc)

#### Final evaluation metrics (Accuracy, F1 Score)

requirements.txt

transformers

datasets

peft

torch

scikit-learn

jupyter

notebooks/Assignment7_FineTuning.ipynb

Section 1: Data Loading

Import Hugging Face dataset (e.g., imdb)

Tokenization with model’s tokenizer

Train/validation/test split

Section 2: Base Model Setup

Load pre‑trained model (BERT, RoBERTa, or T5 variant)

Add classification head

Section 3: PEFT/LoRA Setup

Configure LoRA parameters (r, alpha, dropout)

Inject trainable matrices into model layers

Section 4: Training

Fine‑tune for a few epochs

Track loss/accuracy per epoch

Section 5: Evaluation

Report Accuracy, Precision, Recall, F1‑Score

Compare against baseline (non‑fine‑tuned model)

Section 6: Demo Predictions

Run test cases (positive/negative sentiment, ambiguous text)

Show model output

/assets/

Screenshots or plots (training curves, confusion matrix) for README and video demo
