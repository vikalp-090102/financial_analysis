## Overview

In this study, we adapt Microsoft's phi-3 mini model using Low-Rank Adaptation (LoRA) to classify financial texts into three sentiment categories: positive, negative, and neutral. We fine-tune the model on the Financial PhraseBank dataset, employing strategic prompt engineering and experimenting with different low-rank settings (r = 16, 8, and 4).

## Key Features

- **Parameter-Efficient Fine-Tuning:** Utilizes LoRA to efficiently adapt the phi-3 mini model.
- **Competitive Performance:** Achieves an overall accuracy of 88%, closely matching FinBERT’s 88.93% accuracy.
- **Enhanced Negative Sentiment Detection:** Demonstrates a superior F1-score in detecting negative sentiment, a critical aspect of financial analysis.
- **Cost-Effective & Flexible:** Offers a promising alternative to resource-intensive, domain-specific LLMs.

## Experimentation and Results

- **Dataset:** Financial PhraseBank dataset for training and evaluation.
- **Fine-Tuning Settings:** Experiments conducted with LoRA ranks of 16, 8, and 4.
- **Performance:** The phi-3 mini model, even without extensive pre-training on financial data, delivers competitive results and robustness, particularly in negative sentiment detection.



Note: Please upload given csv file to the ipynb environment and run entire code.
