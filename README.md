# **Natural Language Processing Tasks with Transformers**

## **Overview**

This repository contains two Jupyter notebooks that demonstrate various Natural Language Processing (NLP) tasks using Hugging Face’s Transformers library. These notebooks explore text classification and a variety of other NLP tasks.
## Notebooks
# 1. NLP_tasks_with_Transformers.ipynb
This notebook demonstrates multiple NLP tasks, including:

- Classifying Whole Sentences: Sentiment analysis using a pre-trained model.
- Named Entity Recognition (NER): Identifying entities within text, such as organizations, people, and locations.
- Question Answering: Answering questions based on a given context.
- Text Summarization: Summarizing large blocks of text into concise versions.
- Fill in the Blanks: Completing sentences with missing words using a pre-trained model.
Translation: Translating text from one language to another (e.g., English to German).

# 2. IMDB_text_classification.ipynb
This notebook focuses on classifying movie reviews from the IMDB dataset using a pre-trained model from Hugging Face. It demonstrates:

- Text Classification: Predicting the sentiment of movie reviews (positive or negative) using transformers.
- Model Evaluation: Evaluating the performance of the classifier on the test dataset.

## **Installation**

To run this project, ensure you have Python (version 3.6 or higher) and the required libraries installed.

### 1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
```

### 2. Install the Required Dependencies

```pip install flask transformers datasets tensorflow rouge-score
pip install transformers[sentencepiece]
```
