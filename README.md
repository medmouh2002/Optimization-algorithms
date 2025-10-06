# 🔧 Optimization Algorithms 

This part contains implementations of **optimization algorithms** applied to classic computational problems.  
The projects demonstrate skills in **heuristic search, evolutionary algorithms, and combinatorial optimization** using Genetic Algorithms, Nearest Neighbor, and Local Search techniques.

---

## 📂 Problems Solved

### 1. **Traveling Salesman Problem (TSP) - Berlin52 Dataset** (`IRIS_Dataset.ipynb`)  
- **Problem Type**: Combinatorial Optimization  
- **Dataset**: Berlin52 TSP instance (52 cities in Berlin)  
- **Algorithms Implemented**:  
  - Nearest Neighbor Heuristic  
  - Genetic Algorithm with 2-opt Local Search  
- **Optimization Focus**: Minimize total tour distance for city visitation route.  

---

### 2. **Iris Dataset Clustering - Medoid Selection**  
- **Problem Type**: Clustering Optimization  
- **Dataset**: Iris flower dataset (150 samples, 4 features, 3 classes)  
- **Algorithm Implemented**: Genetic Algorithm for Medoid Selection  
- **Optimization Focus**: Find optimal medoids to minimize intra-cluster distances.  

---

## 🛠️ Technical Projects & Skills Demonstrated

### 🔹 Heuristic Search Methods  
- Nearest Neighbor: Greedy constructive heuristic for TSP initialization.  
- Path Optimization: Sequential city selection based on proximity.  

### 🔹 Evolutionary Algorithms  
- Genetic Algorithm Framework: Population initialization, selection, crossover, mutation.  
- Fitness Evaluation: Distance-based fitness functions for both TSP and clustering.  
- Adaptive Parameters: Dynamic mutation rates based on generation progress.  

### 🔹 Local Search Integration  
- 2-opt Optimization: Edge exchange for local improvement in TSP.  
- Hybrid Approach: Combine global search (GA) with local refinement.  

### 🔹 Solution Representation & Encoding  
- Permutation Encoding: Path representation for TSP solutions.  
- Binary Encoding: Medoid selection for clustering.  
- Constraint Handling: Ensures valid tours and cluster assignments.  

### 🔹 Performance Optimization  
- Distance Matrix Precomputation: Efficient Euclidean distance calculations.  
- Elitism Strategy: Preserving best solutions across generations.  
- Termination Conditions: Target distance thresholds or generation limits.  

### 🔹 Problem-Specific Adaptations  
- TSP Operators: Order crossover, path mutation.  
- Clustering Metrics: Intra-cluster distance minimization.  
- Medoid Assignment: Optimal cluster center selection.  

---

## 🛠️ Technical Environment
- **Languages**: Python  
- **Libraries**: NumPy, SciPy, scikit-learn  
- **Algorithms**: Genetic Algorithms, Nearest Neighbor, 2-opt Local Search  
- **Domains**: Combinatorial Optimization, Clustering, Route Planning  
- **Skills**: Algorithm Design, Heuristic Methods, Evolutionary Computation, Performance Tuning  

---

## 📊 Key Achievements
- **TSP Optimization**: Reduced tour distance from **11,397 (NN)** to **7,598 (GA + 2-opt)** → **33% improvement**.  
- **Clustering Solution**: Automated medoid selection for Iris dataset partitioning.  
- **Algorithm Hybridization**: Demonstrated effectiveness of combining global (GA) and local (2-opt) search methods.  

---
