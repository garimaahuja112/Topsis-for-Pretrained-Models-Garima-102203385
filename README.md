# Pretrained Model Evaluation for Text Summarization using TOPSIS 
This project evaluates multiple pretrained models for text summarization using the **TOPSIS** (Technique for Order of Preference by Similarity to Ideal Solution) method to identify the best model for summarization tasks.

## Models Evaluated
The following pretrained models were evaluated for text summarization:

- **facebook/bart-large-cnn**: Optimized for summarizing news articles and long-form texts.
- **google/pegasus-cnn_dailymail**: A Pegasus model fine-tuned on the CNN/DailyMail dataset.
- **t5-small**: A lightweight version of the T5 model, optimized for various NLP tasks.
- **t5-base**: A larger version of T5, designed for more complex tasks.
- **t5-large**: A larger variant of T5, optimized for handling large-scale summarization tasks.

## Evaluation Criteria
Models were assessed based on the following factors:

- **ROUGE-1**: Measures how much the generated summary matches the original text at the word level.
- **ROUGE-2**: Measures how much the generated summary matches the original text at the two-word combination level.
- **ROUGE-L**: Measures the longest matching subsequence in the generated summary to judge fluency and readability.
- **Inference Time**: The time it takes for the model to generate a summary (important for real-time applications).
- **Model Size**: The memory footprint of the model in MB.

## Results
After evaluating the models using TOPSIS, the following results were obtained:

**Best Model**: `t5-small` 

t5-small achieved the highest rank across multiple summarization tasks, excelling in ROUGE scores, inference time, and model size. It consistently performed well and proved to be the most effective model for general text summarization tasks.
