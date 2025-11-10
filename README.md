# Medical QA: TF-IDF Retrieval vs T5 Generation

Patient-focused medical Q&A is explored using TF-IDF retrieval and a fine-tuned T5-small transformer. Includes preprocessing, feature engineering, and ROUGE evaluation. TF-IDF excels on repetitive data, while T5 generates flexible, paraphrased answers for real-world healthcare use.

## Features

- TF-IDF retrieval baseline for efficient question answering  
- Fine-tuned T5-small transformer for generative Q&A  
- Text preprocessing: cleaning, tokenisation, lemmatisation  
- Evaluation using ROUGE metrics for answer quality  
- Comparison of retrieval accuracy vs generative flexibility  

## Dataset

- `db_nhs_qa.zip`: Collection of medical Q&A documents  
- `patient_qa_train.csv` & `patient_qa_test.csv`: Training and test question-answer pairs  

## Installation

```bash
git clone <repo-url>
cd <repo-folder>
pip install -r requirements.txt
