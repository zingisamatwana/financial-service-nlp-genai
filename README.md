# NLP & Generative AI Experiments

This repository contains **Natural Language Processing (NLP) and Generative AI experiments** for **financial services applications**, specifically focused on **customer sentiment analysis, chatbot development, and marketing analytics**  

# Project Overview

> **Chatbot Development & Enhancement** – Fine-tuning AWS Lex chatbot for customer queries.
> **Fnancial Sentiment Analysis** – Using NLP to analyze customer feedback and financial documents.
> **Generative AI for Customer Insights** – Applying LLMs (GPT-4, FinBERT) for financial conversations.
> **Marketing AI Models** – NLP-powered segmentation and engagement prediction.

# Repository Structure

financial-service-nlp-genai/
│── datasets/                    # Financial NLP datasets
│   ├── financial_phrasebank.csv  # Sentiment-labeled finance data
│   ├── customer_reviews.json     # Customer complaints & feedback
│   ├── earnings_reports.txt      # SEC filings for analysis
│
│── models/                       # Trained NLP models
│   ├── finbert_model/            # Fine-tuned BERT for finance
│   ├── smart_goals_chatbot/      # AWS Lex chatbot model
│
│── notebooks/                    # Jupyter Notebooks for NLP
│   ├── 01_data_preprocessing.ipynb       # Data cleaning & preprocessing
│   ├── 02_sentiment_analysis.ipynb       # Predict customer sentiment
│   ├── 03_finetune_bert_gpt.ipynb        # Fine-tuning BERT/GPT for financial tasks
│   ├── 04_chatbot_training.ipynb         # Training AWS Lex chatbot
│   ├── 05_marketing_nlp_analysis.ipynb   # NLP-driven customer segmentation
│
│── src/                          # Source code for training & inference
│   ├── chatbot_pipeline.py       # AWS Lex chatbot training script
│   ├── sentiment_analysis.py     # Fine-tuned sentiment classifier
│   ├── data_loader.py            # Loads & preprocesses datasets
│   ├── fine_tune_llm.py          # Script to fine-tune GPT/FinBERT
│
│── results/                      # Model outputs & reports
│   ├── chatbot_logs/             # Logs from chatbot conversations
│   ├── nlp_predictions.csv       # Predicted sentiment for customer queries
│
│── configs/                      # Model & API configurations
│   ├── lex_bot_config.json       # AWS Lex chatbot settings
│   ├── huggingface_model.yaml    # Config for fine-tuning transformers
│
│── README.md                      # Project documentation
│── requirements.txt                # Dependencies (transformers, AWS SDK, etc.)
│── .gitignore                      # Ignore unnecessary files

🛠️ Setup & Installation

1. Clone the repository:
```bash
git clone https://github.com/zingisamatwana/financial-service-nlp-genai.git

pip install -r requirements.txt
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run Jupyter Notebooks:
```bash
jupyter notebook
```
4. Start experimenting in notebooks (notebooks/ folder).

5. Commit & push changes to GitHub:
```bash
git add .
git commit -m "Initial NLP experiments"
git push origin main
```

🚀 Key Features

* Fine-Tuned Transformers – BERT, FinBERT, GPT for finance-related tasks.
* Fine-Tuned LLMs (GPT, BERT, FinBERT) – Create custom models for financial conversations.
* AWS Lex Chatbot Integration – Enhancing financial assistant chatbot.
* Customer Sentiment Analysis – NLP model for analyzing customer feedback.
* Marketing AI – NLP-driven customer segmentation for campaigns.
* End-to-End NLP Pipeline – From data preprocessing → training → deployment.
* Marketing NLP Insights – Build predictive models for customer engagement.
* Structured Workflow – Separate datasets, notebooks, source code, and results.

🤖 Next Steps

* Train FinBERT on Old Mutual customer queries.

* Deploy GPT-based chatbot enhancements.

* Integrate NLP insights into marketing workflows.

💡Contributions & Feedback: Open to collaboration! If you have suggestions, feel free to create an issue or pull request.

📧 Contact: Zingisa Matwana | Data Scientist