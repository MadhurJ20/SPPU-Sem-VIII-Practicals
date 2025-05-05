# SPPU Semester VIII Laboratory Assignments

This repository contains practical assignments for Semester VIII of SPPU Computer Engineering.

## LP-V: Laboratory Practice V

### 1. Deep Learning Laboratory (DLL)
Implementation of various deep learning models and techniques using TensorFlow:
- [Boston Housing Price Prediction](LP-V/DLL/DLL_Exp_01.py) (Regression)
- [IMDB Movie Review Sentiment Analysis](LP-V/DLL/DLL_Exp_02.py) (Binary Classification)
- [Fashion MNIST Classification using CNN](LP-V/DLL/DLL_Exp_03.py) (Multi-class Classification)

[View Deep Learning Lab →](LP-V/DLL/)

### 2. High Performance Computing Laboratory (HPCL)
Parallel computing implementations using OpenMP, Python multiprocessing, and CUDA:

#### Graph Algorithms
- [C++ Implementation (BFS/DFS)](LP-V/HPCL/HPCL_Exp_01.cpp)
- [Python Implementation (BFS)](LP-V/HPCL/HPCL_Exp_01.py)

#### Sorting Algorithms
- [C++ Implementation](LP-V/HPCL/HPCL_Exp_02.cpp) (Parallel Bubble Sort, Merge Sort)
- [Python Implementation](LP-V/HPCL/HPCL_Exp_02.py) (Parallel Bubble Sort, Merge Sort)

#### Reduction Operations
- [C++ Implementation](LP-V/HPCL/HPCL_Exp_03.cpp) (OpenMP)
- [Python Implementation](LP-V/HPCL/HPCL_Exp_03.py) (Multiprocessing)

#### Vector and Matrix Operations
##### CUDA Implementation
- [Vector Addition](LP-V/HPCL/HPCL_Exp_04_vector_addition.cu)
- [Matrix Multiplication](LP-V/HPCL/HPCL_Exp_04_matrix_multiplication.cu)

##### OpenMP Implementation
- [Vector Addition](LP-V/HPCL/HPCL_Exp_04_vector_addition.cpp)
- [Matrix Multiplication](LP-V/HPCL/HPCL_Exp_04_matrix_multiplication.cpp)

[View HPC Lab →](LP-V/HPCL/)

## LP-VI: Laboratory Practice VI

### 1. Business Intelligence Laboratory (BIL)
Tools and techniques for business intelligence and data analytics:
- Data Warehousing and ETL
- OLAP and Data Mining
- Data Visualization and Dashboards
- Predictive Analytics

[View BI Lab →](LP-VI/BIL/)

### 2. Natural Language Processing Laboratory (NLPL)
Implementation of NLP algorithms and techniques:
- Text Preprocessing and Feature Extraction
- Text Classification
- Language Models and Word Embeddings
- Machine Translation
- Information Extraction

[View NLP Lab →](LP-VI/NLPL/)

## Dataset Information

### Deep Learning Lab Datasets
- Boston Housing Dataset: 506 samples with 13 features for regression
- IMDB Movie Reviews: 50,000 movie reviews for sentiment analysis
- Fashion MNIST: 70,000 grayscale images (60,000 training, 10,000 testing) in 10 classes

### HPC Lab Test Data
All HPC experiments use generated datasets to demonstrate scalability:
- Graph Search: Random graphs of varying sizes (1K-1M vertices)
- Sorting: Random integer arrays of different sizes (10K-10M elements)
- Reduction: Large arrays of floating-point numbers (1M-100M elements)
- Vector/Matrix Operations: 
  - Vectors: 1M-50M elements
  - Matrices: 100×100 to 1000×1000 elements

## Repository Structure
```
.
├── LP-V/
│   ├── DLL/    # Deep Learning Laboratory
│   │   ├── DLL_Exp_01.py         # Boston Housing Price Prediction
│   │   ├── DLL_Exp_02.py         # IMDB Sentiment Analysis
│   │   ├── DLL_Exp_03.py         # Fashion MNIST Classification
│   │   ├── requirements.txt      # Python dependencies
│   │   └── README.md            # Lab documentation
│   └── HPCL/   # High Performance Computing Laboratory
│       ├── HPCL_Exp_01.{cpp,py}    # Graph Algorithms
│       ├── HPCL_Exp_02.{cpp,py}    # Sorting Algorithms
│       ├── HPCL_Exp_03.{cpp,py}    # Reduction Operations
│       ├── HPCL_Exp_04_*.cu        # CUDA Programs
│       ├── HPCL_Exp_04_vector_addition_omp.cpp  # OpenMP Vector Addition
│       ├── HPCL_Exp_04_matrix_multiplication.cpp  # OpenMP Matrix Multiplication
└── LP-VI/
    ├── BIL/    # Business Intelligence Laboratory
    └── NLPL/   # Natural Language Processing Laboratory
```

## Getting Started
Each laboratory folder contains its own README with:
- Detailed program descriptions
- Setup instructions
- Dependencies and requirements
- Execution instructions
- Additional resources and documentation

## Contributing
Feel free to contribute to this repository by:
- Adding new implementations
- Improving documentation
- Fixing bugs
- Adding test cases
