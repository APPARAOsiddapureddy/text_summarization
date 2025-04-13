# 📝 Text Summarization using Information Retrieval Techniques

This project implements a basic text summarization tool using Python, built as part of the **Information Retrieval course**. It leverages core IR concepts such as preprocessing, inverted indexing, and frequency-based ranking to find and summarize the most relevant content from a set of documents. A simple GUI allows users to interact with the system.

---

## 📁 Project Structure

text-summarization/ │ 
├── gui.py # GUI interface for user interaction 
├── preprocess.py # Preprocessing (cleaning, stopword removal, tokenization) 
├── indexing.py # Handles the indexing of documents 
├── inverted_index.py # Builds an inverted index from processed documents 
├── inverted_index.csv # Stores the generated inverted index in CSV format 
├── wordcount_after_preprocess.py # Word frequency count after preprocessing 
├── top_documents.py # Ranks and displays top documents based on query 
├── summarizer.py (optional) # (Optional) Creates frequency-based summaries 
├── README.md # Project documentation (this file)



---

## 🧰 Features

- ✅ Document preprocessing (tokenization, stopword removal, stemming)
- ✅ Inverted index generation for fast lookup
- ✅ Word frequency tracking post-preprocessing
- ✅ Ranking and retrieval of top documents based on query relevance
- ✅ Simple and intuitive GUI for user interaction
- ✅ Support for summarizing `.txt` files from a local folder

---

## 🚀 Getting Started

### 📦 Prerequisites

- Python 3.x

### 📥 Installation

Clone this repository:

```bash
git clone https://github.com/your-username/text-summarization.git
cd text-summarization
