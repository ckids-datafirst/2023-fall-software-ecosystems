---
title: Approach
summary: Data science methodology used to address the problem, including data preprocessing steps, exploratory data analysis, feature engineering techniques, machine learning models, and evaluation metrics.
date: "2018-06-28T00:00:00Z"
editable: false
share: false
---

## Data Preprocessing

The raw data follows a format that can be used to parse it and extract clean messages. However, there are still some residues that cannot be removed. We use regular expressions to minimize the amount of residues in the clean messages.

## Model Development

We tried out different large language models to perform keyword extraction and summarization. Several models from [Hugging Face](https://huggingface.co/) are evaluated. We follow the description of the model on the website to implement them. In addition, we have designed several functions using the OpenAI models and Llama2 through API calls.

## Model Evaluation

We randomly selected 20 messages to evaluate the performance of different large language models. For keyword extraction, we compare model predictions with manually generated results by counting the number of missed and matched keywords. To evaluate the performance of the text summarization, we calculated the number of keywords retained in the summary compared to the original text. For both tasks, we compute the precision, recall, and f1 score of each model and compare their performance.
