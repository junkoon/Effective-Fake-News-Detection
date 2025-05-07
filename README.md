# Effective Fake News Detection

This repository contains all stages of development for the **Effective Fake News Detection** project. Each notebook highlights a different aspect of the project, from initial data exploration to the final optimized model incorporating advanced features.

---

## Repository Structure

- **`BERT/`**  
  Contains code, experiments, and model implementations using BERT for fake news classification.

- **`RoBERTa/`**  
  Contains code and experiments with RoBERTa applied to fake news detection.

- **`LSTM/`**  
  Contains code and experiments with LSTM-based models for classifying fake news.

- **`Comparison across feature set.ipynb`**  
  A single Jupyter Notebook that uses a Forest Classifier to compare different metadata feature sets (Title-only vs. Title+URL). This notebook investigates if augmenting title features with URL metadata enhances detection accuracy.

- **`data/`**  
  Contains the datasets used in the project (e.g., `fake.csv` and `real.csv`).

- **Other Files:**  
  - `requirements.txt`: List of required Python libraries.  
  - `README.md`: Provides an overview of the project.
---

## Notebooks

### 1. Comparison Across Feature Set

- **File:** `Comparison across feature set.ipynb`  
- **Objective:**  
  - Benchmark the impact of different feature sets by comparing models that use only the title versus those that integrate both title and URL metadata.  
  - Evaluate performance using a Forest Classifier as a baseline to understand how metadata affects fake news detection accuracy.  
  - Provide actionable insights into which combination of features delivers the best results.

---

## Results

The progression from notebooks shows:
1. Basic trends and differences in the dataset.
2. Text-based models can achieve reasonable accuracy but have limitations.
3. Integrating link analysis significantly enhances detection performance.

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Effective-Fake-News-Detection.git
   cd Effective-Fake-News-Detection

2. Install Dependencies:
   ```bash
   pip install -r requirements.txt

3. Run Notebooks
   ```bash
   jupyter notebook

