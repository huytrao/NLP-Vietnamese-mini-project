# NLP Vietnamese Mini-Project

A comprehensive collection of Natural Language Processing (NLP) implementations and experiments focusing on Vietnamese text processing and various NLP techniques.

## 📖 Overview

This repository contains multiple Jupyter notebooks demonstrating various NLP concepts, from fundamental text processing to advanced transformer models. The projects primarily use Vietnamese datasets, particularly the UIT-VSFC (Vietnamese Students' Feedback Corpus) for sentiment analysis tasks.

## 🚀 Projects

### 1. **BERT & XLNet Emotion Detection (Vietnamese)**
- **File**: `BERT_XLNET_Emotion Detection-vi.ipynb`
- **Description**: Implementation of BERT and XLNet models for Vietnamese sentiment classification
- **Dataset**: UIT-VSFC Vietnamese Students' Feedback Corpus
- **Key Features**:
  - Fine-tuning pre-trained BERT and XLNet models
  - Sentiment classification on Vietnamese text
  - Model comparison and performance analysis
  - Visualization of training metrics and results

### 2. **English Transformer Models (BERT & XLNet)**
- **File**: `EN-Transfromer_XLNET_BERT-emotion_detection.ipynb`
- **Description**: English emotion detection using transformer models
- **Key Features**:
  - BERT and XLNet implementation for English text
  - Emotion classification tasks
  - Model performance comparison

### 3. **Global Vectors for Word Representation (GloVe)**
- **File**: `Global_Vectors_for_Word_Representation.ipynb`
- **Description**: Implementation of GloVe word embeddings from scratch
- **Key Features**:
  - GloVe algorithm implementation
  - Word co-occurrence matrix construction
  - Word embedding visualization
  - Semantic similarity analysis

### 4. **LSTM Text Summarization**
- **File**: `LSTM-summarise-text.ipynb`
- **Description**: Text summarization using LSTM networks
- **Key Features**:
  - Sequence-to-sequence architecture
  - News article summarization
  - LSTM encoder-decoder implementation
  - Text preprocessing and tokenization

### 5. **Sequence-to-Sequence with Attention**
- **File**: `Sequence_to_Sequence_and_attention.ipynb`
- **Description**: Implementation of seq2seq models with attention mechanism
- **Key Features**:
  - Encoder-decoder architecture
  - Attention mechanism implementation
  - Language translation or text generation tasks
  - PyTorch implementation

### 6. **Skip-gram and CBOW Word Embeddings**
- **File**: `skipgram_cbow.ipynb`
- **Description**: Implementation of Word2Vec models (Skip-gram and CBOW)
- **Key Features**:
  - Skip-gram model implementation
  - Continuous Bag of Words (CBOW) model
  - One-hot encoding demonstration
  - Word embedding training and evaluation

### 7. **Text Processing, Stopwords & TF-IDF**
- **File**: `text_processing_stopword_tfidf.ipynb`
- **Description**: Fundamental text preprocessing and feature extraction
- **Dataset**: UIT-VSFC Vietnamese Students' Feedback Corpus
- **Key Features**:
  - Vietnamese text preprocessing
  - Stopword removal
  - TF-IDF vectorization
  - N-gram analysis
  - Text normalization techniques

## 🔧 Requirements

### Python Packages
```bash
# Core ML/DL libraries
torch>=2.0.1
torchtext==0.15.2
transformers
datasets
sklearn

# Text processing
spacy
nltk
underthesea  # Vietnamese NLP toolkit

# Data manipulation and visualization
numpy
pandas
matplotlib
seaborn

# Utilities
fsspec
wget
```

### Installation
```bash
# Install required packages
pip install -r requirements.txt

# Download spaCy models
python -m spacy download en_core_web_sm

# For Vietnamese text processing
pip install underthesea
```

## 📊 Datasets

### Primary Dataset: UIT-VSFC
- **Full Name**: Vietnamese Students' Feedback Corpus
- **Size**: 16,000+ sentences
- **Tasks**: Sentiment analysis and topic classification
- **Language**: Vietnamese
- **Source**: University of Information Technology (UIT)
- **Citation**: 
  ```
  Kiet Van Nguyen, Vu Duc Nguyen, Phu Xuan-Vinh Nguyen, Tham Thi-Hong Truong, Ngan Luu-Thuy Nguyen, 
  "UIT-VSFC: Vietnamese Students' Feedback Corpus for Sentiment Analysis", 
  2018 10th International Conference on Knowledge and Systems Engineering (KSE 2018)
  ```

### Additional Datasets
- **Text8 Corpus**: For word embedding training (GloVe implementation)
- **News Summary Dataset**: For text summarization tasks

## 🏃‍♂️ Quick Start

1. **Clone the repository**:
```bash
git clone https://github.com/huytrao/NLP-Vietnamese-mini-project.git
cd NLP-Vietnamese-mini-project
```

2. **Install dependencies**:
```bash
pip install -r requirements.txt
```

3. **Choose and run a notebook**:
```bash
jupyter notebook <notebook_name>.ipynb
```

## 📈 Model Performance

### BERT vs XLNet (Vietnamese Sentiment Analysis)
- Both models fine-tuned on UIT-VSFC dataset
- Comparison includes accuracy, F1-score, and training time
- Detailed analysis available in the respective notebook

### Word Embedding Models
- Skip-gram vs CBOW performance comparison
- GloVe implementation results
- Semantic similarity evaluations

## 🛠️ Implementation Details

### Transformer Models (BERT/XLNet)
- **Framework**: Hugging Face Transformers
- **Pre-trained Models**: 
  - `bert-base-multilingual-cased` for Vietnamese
  - `xlnet-base-cased` for English/multilingual tasks
- **Fine-tuning**: Task-specific classification heads
- **Evaluation**: Accuracy, Precision, Recall, F1-score

### Traditional NLP Techniques
- **Text Preprocessing**: Tokenization, normalization, stopword removal
- **Feature Extraction**: TF-IDF, N-grams
- **Word Embeddings**: Word2Vec (Skip-gram, CBOW), GloVe
- **Sequence Models**: LSTM, Seq2Seq with attention

## 📚 Learning Outcomes

This project demonstrates:
- **Vietnamese NLP**: Specialized techniques for Vietnamese text processing
- **Transformer Architecture**: Understanding and implementation of BERT, XLNet
- **Traditional NLP**: Fundamental concepts like TF-IDF, word embeddings
- **Deep Learning**: LSTM, attention mechanisms, encoder-decoder architectures
- **Comparative Analysis**: Model performance evaluation and comparison
- Focus: Natural Language Processing and Machine Learning

## 📄 License

This project is for educational purposes. Please refer to individual dataset licenses for commercial use.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📞 Contact

For questions or collaboration opportunities, please reach out through GitHub issues or discussions.

---

This repository serves as a comprehensive learning resource for Vietnamese NLP and various machine learning techniques in natural language processing.
