# AdabEval 2026 – Politeness Classification

This repository contains our system for participating in **AdabEval 2026**, a shared task on politeness classification in Arabic social media posts, hosted at OSACT7 and co-located with LREC 2026.

## Task Overview
We participate in **Subtask A: Politeness Classification**, where the goal is to classify Arabic social media posts into:
- Polite
- Neutral
- Impolite

## Dataset
The dataset consists of annotated Arabic social media posts, each labeled with a politeness category.  
The dataset is provided by the AdabEval 2026 organizing team and is used strictly for research purposes.

## Project Structure
AdabEval2026-Politeness-Classification/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── EDA.ipynb
│
├── preprocessing/
│   ├── clean_text.py
│
├── models/
│   ├── train.py
│   ├── evaluate.py
│
├── experiments/
│   ├── baseline_results.md
│
├── results/
│   ├── metrics.json
│   ├── confusion_matrix.png
│
├── paper/
│   ├── system_description_draft.md
│
├── requirements.txt
└── README.md


## Methodology
- Text preprocessing and normalization
- Transformer-based Arabic language models (e.g., AraBERT, MARBERT)
- Multi-class classification
- Evaluation using Accuracy and Macro F1-score

## Evaluation Metrics
- Accuracy
- Macro-averaged Precision
- Recall
- F1-score

## Team
Sara Aljuraybah
## License
This project is for academic and research use only.

