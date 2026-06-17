# AI CUP 2026 ESG Promise Verification

## Project Overview

This project participates in AI CUP 2026 ESG Promise Verification.

The goal is to classify ESG commitment statements using a Chinese RoBERTa model and predict multiple ESG-related labels.

---

## Model

- Model: hfl/chinese-roberta-wwm-ext
- Framework: PyTorch
- Tokenizer: HuggingFace Transformers

---

## Classification Tasks

This project performs multi-task classification:

1. promise_status
2. verification_timeline
3. evidence_status
4. evidence_quality

---

## Training Process

1. Load ESG dataset
2. Data preprocessing
3. Tokenization using RoBERTa tokenizer
4. Multi-task model training
5. Validation using Macro F1 score
6. Generate prediction.json

---

## Files

| File | Description |
|--------|--------|
| 2026_ai_cup.ipynb | Training and prediction code |
| prediction.json | Prediction results |
| training_curve.png | Training curve |
| f1_scores.png | F1 score results |
| label_distribution.png | Label distribution |

---

## Author

YU XIANG LIU
Webber Hao

Department of Electrical Engineering

National Kaohsiung University of Science and Technology (NKUST)

2026
