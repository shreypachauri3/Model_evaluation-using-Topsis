# Text Generation Model Evaluation using TOPSIS

## Overview

This project focuses on the evaluation of text generation models using the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) method. The TOPSIS analysis is performed on key evaluation metrics to rank the performance of various text generation models.

## Model Ranking Table

The following table presents the ranking of text generation models based on different evaluation metrics:

```markdown
| Rank | Model                    | Accuracy | F1_Score | Precision | Recall |
|------|---------------------------|----------|----------|-----------|--------|
| 1.0  | distilbert-base-uncased   | 0.88     | 0.91     | 0.89      | 0.90   |
| 2.0  | roberta-base              | 0.87     | 0.90     | 0.88      | 0.89   |
| 3.0  | t5-base                   | 0.89     | 0.92     | 0.91      | 0.80   |
| 4.0  | electra-base              | 0.86     | 0.89     | 0.87      | 0.88   |
| 5.0  | bert-base-uncased         | 0.85     | 0.89     | 0.88      | 0.87   |
| 6.0  | gpt2                      | 0.82     | 0.87     | 0.85      | 0.84   |
