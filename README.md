# Text Summarization with Machine Learning and NLP

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mirhuseyn-Javadzada/Text-Summarization-Algorithm/blob/main/texts_algorithms.ipynb)


## Overview
This repository presents a Jupyter Notebook focused on **automatic text summarization**. The project reduces long dialogues and texts into concise summaries while preserving their essential meaning. Text summarization is a key task in **Natural Language Processing (NLP)** with applications in news aggregation, conversational AI, academic research, and information retrieval.

The notebook combines **data preprocessing**, **statistical NLP methods**, and **state-of-the-art deep learning models** to demonstrate different approaches to text summarization.

---

## Dataset
The project uses the **SAMSum Dataset**, which contains thousands of dialogues paired with human-written summaries. This dataset is widely used for training and evaluating summarization models.

---

## Methods and Algorithms
The notebook explores multiple approaches:

- **Preprocessing**  
  - Removing missing values  
  - Cleaning HTML tags and noisy data  
  - Tokenization and word count analysis  

- **Statistical Feature Extraction**  
  - **TF-IDF Vectorizer**: Identifies the most relevant words in dialogues.  

- **Visualization**  
  - Histograms and boxplots of dialogue/summary lengths.  

- **Machine Learning and NLP Models**  
  - **TF-IDF-based Extractive Summarization**  
  - **Transformer-based Abstractive Summarization** using **BART (`facebook/bart-large-xsum`)**  

---

## Structure of the Notebook
1. **Introduction** – Overview of summarization and dataset.  
2. **Data Loading and Cleaning** – Reading SAMSum CSV files and cleaning text.  
3. **Exploratory Analysis** – Word count distributions and visualization.  
4. **Feature Extraction** – TF-IDF vectorization.  
5. **Summarization Models** – Extractive and abstractive approaches.  
6. **Examples and Results** – Summaries generated for sample texts.  

---

## How to Use
1. Clone this repository:
2. ```bash
   git clone https://github.com/your-username/texts_algorithms.git
## cd texts_algorithms
## jupyter notebook texts_algorithms.ipynb

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mirhuseyn-Javadzada/Text-Summarization-Algorithm/blob/main/texts_algorithms.ipynb)


##pip install -r requirements.txt

⚠️ Note: If the notebook does not render correctly on GitHub and shows “Invalid Notebook”, this is caused by metadata issues.

To view and run the notebook, please open it locally with Jupyter Notebook or on Google Colab.

Alternatively, you can remove or fix the metadata.widgets section in the .ipynb file.

   ```bash
   git clone https://github.com/your-username/texts_algorithms.git
