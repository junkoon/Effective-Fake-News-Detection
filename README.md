# Effective Fake News Detection

This repository contains all stages of development for the **Effective Fake News Detection** project. Each notebook highlights a different aspect of the project, from initial data exploration to the final optimized model incorporating advanced features.

---

## Repository Structure

- **`notebooks/`**
  - `Data & Model Comparison.ipynb`: Explores the dataset, comparing fake vs real news using textual features only.
  - `Trial_Model_Without_Link_Analysis.ipynb`: A trial model focused on text analysis without incorporating URLs.
  - `Optimized Model With Link Analysis.ipynb`: Final model that integrates text and link analysis for improved accuracy.

- **`data/`**
  - `fake.csv` and `real.csv`: Datasets used in the project.

- **Other Files**:
  - `requirements.txt`: Contains a list of required Python libraries.
  - `README.md`: Provides an overview of the project.

---

## Notebooks

### 1. Data Comparison
- **File**: `Data & Model Comparison.ipynb`
- **Objective**: 
  - Compare basic characteristics of fake and real news.
  - Evaluate the performance of several fundamental machine learning models
  - Understand trends and differences in textual features.
  - Results from this notebook helped decide whether link analysis was worth pursuing.

### 2. Trial Model Without Link Analysis
- **File**: `Trial_Model_Without_Link_Analysis.ipynb`
- **Objective**: 
  - Develop an initial text-based classification model.
  - Evaluate performance and identify areas for improvement.

### 3. Optimized Model With Link Analysis
- **File**: `Optimized Model With Link Analysis.ipynb`
- **Objective**:
  - Integrate link analysis and textual features.
  - Use advanced embeddings (BERT) alongside URL feature extraction.
  - Achieve a higher accuracy with a comprehensive approach.

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
