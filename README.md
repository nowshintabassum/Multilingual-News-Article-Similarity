# Multilingual-News-Article-Similarity
 AIT-526 NLP Final Project
 <br>

### Dataset Description

- **training_data.csv**  
  - Contains training data version 1.  
  - Each news pair is in the same language.

- **test_data.csv**  
  - Contains test data.

- **enriched_training_data**  
  - Combines training data version 1 and version 2.  
  - Includes cross-lingual article pairs.  
  - Text of articles is labeled with **named entities**.

- **enriched_test_data**  
  - Test data labeled with **named entities**.
 
 ### Notebook Explanations:
 
- Multilingual_News_Article_similarity_NLP_Project notebook consists of data downloading, data compiling, data cleaning techniques, as well as finetuning XLM-Roberta with the initial data
- BERT_Multilingual notebook consists of finetuning BERT-Multilingual with the initial data
- Finetuning_XLM_ROBERTA_with_enriched_dataset notebook consists of loading a pretrained multilingual NER model, enriching the given dataset wiith Named entities and finetuning XLM-Roberta with the enriched dataset
