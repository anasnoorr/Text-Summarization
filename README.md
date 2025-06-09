📝 Text Summarization Project
This project summarizes long news articles into short and meaningful summaries using two types of techniques:

✂️ Extractive Summarization – Picks key sentences from the original text

✨ Abstractive Summarization – Creates new summary sentences using a pre-trained model

⚙️ How to Run
Download the notebook file from this repository

Open it in Google Colab or Jupyter Notebook

💡 What’s Inside
1. Dataset
We used the DailyMail dataset which contains news articles and human-written summaries.

2. Steps in the Code
Load and clean the text

Use spaCy to generate extractive summaries

Use BART model from Hugging Face for abstractive summaries

Show and compare the results with actual highlights

🤖 Libraries Used
pandas

spacy

transformers (Hugging Face)
