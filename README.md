# NLP-Based Autocorrect System

An NLP-based autocorrect system developed using Python and NLTK that automatically suggests the most probable correct words for misspelled user input. The project uses text preprocessing, word frequency analysis, and probability-based prediction techniques to generate accurate autocorrection suggestions.

---

## Features

- Text preprocessing and tokenization
- Word frequency analysis
- Probability-based word prediction
- Candidate word generation
- Spelling correction using:
  - Insertion
  - Deletion
  - Replacement
  - Letter swapping
- Supports custom text datasets

---

## Technologies Used

- Python
- NLTK
- Regular Expressions (Regex)
- NumPy
- Google Colab

---

## Project Workflow

1. Upload text dataset
2. Preprocess and tokenize text
3. Build vocabulary from dataset
4. Calculate word frequencies and probabilities
5. Generate candidate corrections
6. Predict the best correction based on probability

---

## Dataset

The system uses a custom text dataset (`final.txt`) to build vocabulary and calculate word probabilities.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/VaibhavM1122/NLP-Based-Autocorrect-System.git
