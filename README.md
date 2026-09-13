# Generative AI: Sentiment Analysis

This repository contains an implementation of a Generative AI application for analyzing and classifying the emotional tone behind a body of text. It utilizes **Hugging Face models** configured through the high-level `transformers` pipeline for accurate, ready-to-use Natural Language Processing (NLP) inference.

## 🚀 Overview

The project provides an interactive pipeline to evaluate user comments, reviews, or general statements, classifying them into emotional categories such as Positive, Negative, or Neutral. All configuration, classification logic, and result printouts are contained within the `SENTIMENTAL-ANALYSIS.ipynb` Jupyter Notebook.

## 🛠️ Features

* **Hugging Face Pipeline:** Implements the `transformers` high-level pipeline specifically optimized for `sentiment-analysis` tasks.
* **Pre-trained Classifiers:** Leverages fine-tuned transformer architectures (like DistilBERT, BERT, or RoBERTa) out-of-the-box.
* **Confidence Scoring:** Outputs both the semantic label and a statistical confidence score for each input string evaluated.

## 📋 Prerequisites

Before running the notebook, ensure you have the following installed:

* Python 3.8 or higher
* Jupyter Notebook or JupyterLab
* A stable internet connection (to download model checkpoints and tokenizers during initial execution)

## 🔧 Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com
   cd GEN-AI-sentimental-analysis
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install notebook torch transformers
   ```

## 💻 Usage

1. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. Open the **`SENTIMENTAL-ANALYSIS.ipynb`** file via the Jupyter browser dashboard.
3. Input custom text phrases, customer feedback strings, or test logs into the notebook's evaluation strings.
4. Run all execution cells sequentially to pass your text arrays through the classification engine and inspect the parsed results.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.
