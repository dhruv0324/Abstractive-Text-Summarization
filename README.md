# Abstractive Text Summarization using Transformer-based Models

## Overview

In today's information-rich landscape, the deluge of textual data poses a significant challenge, necessitating efficient methods for distilling key information. This project delves into the domain of abstractive text summarization, where the focus lies on generating novel phrases and sentences to convey the essence of the source material. The study evaluates the efficacy of advanced transformer-based models, including PEGASUS, BART, and T5, in the context of abstractive summarization.

## Author

- **Dhruva Sandu**  
  Department of Computer Engineering and Technology  
  Dr. Vishwanath Karad MIT World Peace University, Pune, India  
  Email: dhruvasandu@gmail.com

## Datasets

The models are evaluated on two datasets:
- **BBC News Dataset**: Collection of news articles from the British Broadcasting Corporation.
- **CNN/Daily Mail Dataset**: Collection of news articles from CNN and Daily Mail.

## Methodology

The study employs transformer-based models for abstractive text summarization:
- **PEGASUS**
- **BART**
- **T5**

Performance is assessed using two metrics:
- **ROUGE**: Traditional metric evaluating overlap of n-grams between the reference summary and the generated summary.
- **BERTScore**: A more recent metric leveraging BERT embeddings to evaluate semantic similarity between the reference summary and the generated summary.

## Results

### Best Results

- **BBC News Dataset**:
  - **PEGASUS**:
    - ROUGE-1: 46.5
    - ROUGE-2: 24.3
    - ROUGE-L: 42.8
    - BERTScore: 92.5
- **CNN/Daily Mail Dataset**:
  - **PEGASUS**:
    - ROUGE-1: 45.1
    - ROUGE-2: 22.9
    - ROUGE-L: 41.5
    - BERTScore: 91.8
  - **T5**:
    - ROUGE-1: 44.8
    - ROUGE-2: 22.7
    - ROUGE-L: 41.3
    - BERTScore: 92.0

