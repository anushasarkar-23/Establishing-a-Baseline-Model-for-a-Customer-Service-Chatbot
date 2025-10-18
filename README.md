# Establishing a Baseline Model for a Customer Service Chatbot

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Transformers-yellow?style=for-the-badge)

A mini-project by Anusha Sarkar and Devashree Palav for K. J. Somaiya College of Engineering, demonstrating the fine-tuning of a conversational AI for specialized customer support.

---

## 📋 About The Project

This project addresses the challenge of creating a domain-specific chatbot that can handle customer service interactions. Instead of training a model from scratch, this project uses **transfer learning** to fine-tune the pre-trained `microsoft/DialoGPT-small` model on a real-world dataset of Twitter customer support conversations.

The result is a functional baseline model that serves as a proof-of-concept, capable of generating contextually relevant, albeit sometimes formulaic, responses. It showcases an end-to-end pipeline from raw data processing to interactive model inference.

### Key Features:
* **Data Cleaning & Pairing:** A robust pipeline to process raw tweet logs into a clean, conversational query-reply format.
* **Model Fine-Tuning:** Adaptation of a pre-trained language model to a specific domain using PyTorch and Hugging Face Transformers.
* **Interactive Interface:** A simple command-line interface to chat with the trained bot.
* **Baseline for Future Work:** The model serves as a benchmark for future improvements and more advanced iterations.

### Built With
* [Python](https://www.python.org/)
* [PyTorch](https://pytorch.org/)
* [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
* [Pandas](https://pandas.pydata.org/)
* [Google Colab](https://colab.research.google.com/)

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need Python 3.8+ and the following libraries installed:
```sh
pip install torch
pip install transformers
pip install pandas

Dataset
The twcs.csv dataset is too large for GitHub and is hosted on Google Drive as a zip file.

Instructions:

Download the dataset from this Google Drive link:

Link: [PASTE YOUR GOOGLE DRIVE SHAREABLE LINK HERE] <-- IMPORTANT: REPLACE THIS!

Unzip the file to get twcs.csv.

Place the twcs.csv file in the root directory of this project before running the notebook.
