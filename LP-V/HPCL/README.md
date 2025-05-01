# High Performance Computing Laboratory

## Programs List and Instructions

### 1. Parallel Graph Search (BFS and DFS)

**File**: `parallel_graph_search.cpp`

```bash
# Compile
g++ -fopenmp parallel_graph_search.cpp -o parallel_graph_search
# Run
./parallel_graph_search
```

### 2. Parallel Sorting Algorithms

**Files**:

- `parallel_sorting.cpp`
- `parallel_sorting.py`

C++ version:

```bash
# Compile
g++ -fopenmp parallel_sorting.cpp -o parallel_sorting
# Run
./parallel_sorting
```

Python version:

```bash
python parallel_sorting.py
```

### 3. Parallel Reduction Operations

**Files**:

- `parallel_reduction.cpp`
- `parallel_reduction.py`

C++ version:

```bash
# Compile
g++ -fopenmp parallel_reduction.cpp -o parallel_reduction
# Run
./parallel_reduction
```

Python version:

```bash
python parallel_reduction.py
```

### 4. CUDA Programs

#### Vector Addition

**File**: `vector_addition.cu`

```bash
# Compile
nvcc vector_addition.cu -o vector_addition
# Run
./vector_addition
```

#### Matrix Multiplication

**File**: `matrix_multiplication.cu`

```bash
# Compile
nvcc matrix_multiplication.cu -o matrix_multiplication
# Run
./matrix_multiplication
```

## Requirements

1. For C++ Programs:

   - GCC compiler with OpenMP support
   - C++11 or later

2. For Python Programs:

   - Python 3.x
   - NumPy
   - multiprocessing module

3. For CUDA Programs:
   - NVIDIA CUDA Toolkit
   - NVIDIA GPU with CUDA support
   - CUDA-capable driver

## Notes

- OpenMP programs use 4 threads by default
- Python parallel programs use the available CPU cores
- CUDA programs are optimized for GPUs with compute capability 3.0 or higher
