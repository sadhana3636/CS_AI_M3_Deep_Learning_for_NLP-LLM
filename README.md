#  Deep Learning for NLP : IndustryGPT: Specialized LLM Bot Using Pre-Trained Models
## Retail Banking Chatbot using FLAN-T5

##  Project Overview

This project focuses on developing an AI-powered chatbot for the Retail Banking sector using Google’s FLAN-T5-small Large Language Model (LLM). The chatbot is trained on banking-related conversational data and is capable of generating context-aware and human-like responses for customer support queries.

The chatbot handles banking services such as debit card activation, account inquiries, ATM location, and loan-related queries. The final system is deployed using Gradio for real-time user interaction.

---

##  Project Objective

The main objective of this project is to develop an intelligent banking chatbot capable of understanding and responding to customer queries using Natural Language Processing and transformer-based deep learning techniques.

---

##  Problem Statement

Traditional rule-based banking chatbots often fail to understand natural language queries and provide accurate responses. This project aims to solve this problem by developing an AI-powered chatbot using a fine-tuned FLAN-T5 model for automated banking customer support.

---

## Technologies Used

* Python
* Hugging Face Transformers
* Hugging Face Datasets
* FLAN-T5-small
* Gradio
* Scikit-learn
* Google Colab
* PyTorch

---

##  Dataset Details

## Dataset Used

Bitext Retail Banking LLM Chatbot Training Dataset

## Dataset Features

* Banking-related prompt–response pairs
* Approximately 24,000 records
* CSV format
* Includes customer queries and chatbot responses

## Sample Queries

* How can I activate my debit card?
* How do I apply for a home loan?
* Where is the nearest ATM?

---

#  Data Preprocessing

The dataset was cleaned by removing null values, empty records, and duplicate entries. Relevant columns were selected, and the data was split into training and testing sets. The text data was then tokenized using the FLAN-T5 tokenizer before model training.

---

##  Model Used :  FLAN-T5-small

FLAN-T5 is a transformer-based sequence-to-sequence Large Language Model developed by Google. It is optimized for instruction-following tasks such as chatbot response generation and question answering.

### Why FLAN-T5-small?

* Lightweight and efficient
* Suitable for Google Colab GPU
* Fast training and inference
* Effective for chatbot applications

---

##  Model Training

The FLAN-T5-small model was fine-tuned using banking conversational data.

### Training Configuration

* Epochs: 3
* Batch Size: 4
* Optimizer: AdamW
* Learning Rate: 2e-5
* Platform: Google Colab

The Hugging Face `Seq2SeqTrainer` was used for training and evaluation.

---

##  Chatbot Features

* Debit card activation support
* Account-related assistance
* ATM and branch locator support
* Loan inquiry handling
* Context-aware responses
* Real-time chatbot interaction

---

##  Gradio Deployment

Gradio is used to deploy the chatbot as an interactive web application. It allows users to enter banking-related queries and receive AI-generated responses in real time through a browser interface.

---

##  Model Evaluation

The chatbot was evaluated based on:

* Response relevance
* Context understanding
* Human-like response generation

The model successfully generated meaningful responses for banking-related customer queries.

---

##  Future Scope

* Integration with live banking systems
* Multilingual support
* Voice-based interaction
* Enhanced security and authentication
* Expansion to additional financial services

---

##  Conclusion

This project successfully demonstrates the development of an AI-powered Retail Banking Chatbot using a fine-tuned FLAN-T5 Large Language Model. The chatbot generates meaningful and context-aware responses for banking customer queries and highlights the practical application of NLP and deep learning techniques in automating customer support services.

---

##  How to Run the Project

## Install Required Libraries

```python
!pip install transformers datasets gradio scikit-learn
```

## Launch Chatbot

```python
interface.launch()
```

This generates a public Gradio URL for real-time chatbot interaction.



## References

* Hugging Face Transformers Documentation

* Google FLAN-T5 Documentation

* Gradio Documentation

* Hugging Face Transformers Documentation

* Google FLAN-T5 Documentation

* Hugging Face Datasets Library

* Bitext Retail Banking Chatbot Dataset
