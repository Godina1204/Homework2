---

# Homework 2

## Overview

This repository contains the implementation of selected tasks from **Homework 2** in Natural Language Processing (NLP). The primary objectives of this assignment are to

1. Develop a probabilistic **bigram language model** using Maximum Likelihood Estimation (MLE).
2. Implement and analyze a **multi-class confusion matrix** to evaluate the performance of classification models.

The work emphasizes practical understanding of n-gram models, probabilistic estimation, and evaluation metrics commonly used in NLP and ML research.

---

## Repository Contents

* **`bigram_model.py`**

  * Reads a small training corpus.
  * Computes unigram and bigram counts.
  * Estimates bigram probabilities using MLE:
        P(wi​∣wi−1​)=C(wi−1​)C(wi−1​,wi​)​
  * Implements a function to compute the probability of a given sentence.
  * Compares probabilities of candidate sentences to determine which is preferred by the model.

* **`confusion_matrix.py`**

  * Constructs a confusion matrix for multi-class classification.
  * Calculates relevant evaluation metrics (accuracy and related statistics).
  * Demonstrates the application of error analysis in supervised learning.

---

## Requirements

* **Python 3.x**
* Standard libraries:

  * `collections` (for frequency counts)
  * `numpy` (if matrix operations are required)

---





## Example Applications

* **Bigram Model**

  * Given two candidate sentences, the model computes their probabilities and indicates which one is more plausible under the training corpus.
    
## Example Run

  * <img width="1918" height="958" alt="image" src="https://github.com/user-attachments/assets/e91d0f40-ca99-4fa2-91b1-214c6f808876" />


* **Confusion Matrix**

  * Given actual and predicted labels, the script generates a matrix summarizing classification performance, supporting both accuracy measurement and error analysis.

    
## Example Run

  * Confusion-matrix
  * <img width="1189" height="1082" alt="image" src="https://github.com/user-attachments/assets/d188ada1-2cf0-4896-943a-e2588c53b644" />

---

## Learning Objectives

By completing this assignment, one gains experience with:

* Implementing **n-gram language models** and understanding data sparsity issues.
* Applying **Maximum Likelihood Estimation** to compute probabilities in NLP.
* Constructing and interpreting **confusion matrices** for multi-class evaluation.
* Strengthening the connection between theory and practical implementation in NLP/ML tasks.

---

