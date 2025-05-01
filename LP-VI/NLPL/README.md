# Natural Language Processing Laboratory

This laboratory covers practical implementations of Natural Language Processing techniques and algorithms using Python and popular NLP libraries.

## List of Assignments

### 1. Text Preprocessing and Feature Extraction
- Text cleaning and normalization
- Tokenization and lemmatization
- Feature extraction (Bag of Words, TF-IDF)
- N-gram analysis
- Tools: NLTK, spaCy
- Implementation: Text preprocessing pipeline

### 2. Text Classification
- News article categorization
- Sentiment analysis
- Spam detection
- Tools: scikit-learn, Transformers
- Implementation: Multi-class text classifier

### 3. Language Models and Word Embeddings
- Word2Vec implementation
- GloVe embeddings usage
- Contextual embeddings (BERT)
- Tools: gensim, Transformers
- Implementation: Custom embedding model

### 4. Machine Translation
- Rule-based translation
- Statistical machine translation
- Neural machine translation
- Tools: OpenNMT, Transformers
- Implementation: Basic translation system

### 5. Information Extraction
- Named Entity Recognition (NER)
- Relationship extraction
- Part-of-Speech (POS) tagging
- Tools: spaCy, Stanford NLP
- Implementation: NER system

## Setup Instructions

### Prerequisites
1. Python 3.8 or later
2. Virtual environment recommended
3. GPU support (optional, for deep learning)

### Installation
```bash
# Create and activate virtual environment
python -m venv nlp_env
source nlp_env/bin/activate  # Linux/Mac
# or
.\nlp_env\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Download required NLTK data
python -c "import nltk; nltk.download('all')"

# Download spaCy models
python -m spacy download en_core_web_sm
python -m spacy download en_core_web_md
```

## Project Structure
```
NLPL/
├── assignments/
│   ├── preprocessing/
│   ├── classification/
│   ├── embeddings/
│   ├── translation/
│   └── information_extraction/
├── data/
│   ├── raw/
│   └── processed/
├── models/
├── notebooks/
├── src/
│   ├── utils/
│   └── evaluation/
└── requirements.txt
```

## Best Practices

### Code Organization
- Modular code structure
- Clear documentation
- Unit tests for core functionality
- Proper error handling

### Model Development
- Data versioning
- Model checkpointing
- Experiment tracking
- Performance metrics logging
- Cross-validation

### GPU Usage
- Batch size optimization
- Memory management
- Multi-GPU support where applicable
- Performance profiling

## Dataset Information

### Included Datasets
- Sample news articles
- Movie reviews
- Named entity datasets
- Parallel corpora for translation

### External Datasets
- Links to download additional datasets
- Processing scripts
- Data format documentation

## Evaluation Metrics

### Text Classification
- Accuracy, Precision, Recall, F1-score
- Confusion matrix
- ROC curves

### Machine Translation
- BLEU score
- METEOR score
- Translation examples

### Information Extraction
- Entity-level precision/recall
- Span detection accuracy
- Relationship extraction metrics

## Documentation
Each assignment includes:
- Problem statement
- Implementation approach
- Code documentation
- Results analysis
- Error analysis
- Future improvements

## Resources
- Research papers
- Tutorial links
- Documentation references
- Benchmark results
- Common pitfalls and solutions
