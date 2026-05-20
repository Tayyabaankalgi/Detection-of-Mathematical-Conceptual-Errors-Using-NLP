# Detection of Mathematical Conceptual Errors Using NLP and Large Language Models

## Overview

Understanding *why* a student makes a mistake is often more important than simply checking whether the final answer is right or wrong. This project focuses on detecting mathematical misconceptions from students’ written explanations using Natural Language Processing (NLP) and Large Language Models (LLMs).

The system analyzes open-ended student responses from the **MAP – Charting Student Math Misunderstandings** dataset and predicts the most likely conceptual misunderstanding behind each answer. Instead of traditional rule-based evaluation, the project uses transformer-based language models to understand reasoning patterns, contextual meaning, and hidden misconceptions within textual explanations.

This repository contains the complete inference pipeline, preprocessing scripts, model execution workflow, and submission generation process used for the competition.

---

## Problem Statement

Students often provide incorrect answers due to conceptual misunderstandings rather than calculation mistakes. Traditional assessment systems only classify answers as correct or incorrect, without identifying the reasoning error behind them.

The goal of this project is to:

* Analyze student explanations
* Detect conceptual misconceptions
* Classify misunderstanding categories
* Improve educational feedback systems using AI

---

## Dataset

The project uses the **MAP – Charting Student Math Misunderstandings** dataset from Kaggle.

Dataset includes:

* Math diagnostic questions
* Student-selected answers
* Open-ended textual explanations
* Misconception labels

Dataset Link:
[https://www.kaggle.com/competitions/map-charting-student-math-misunderstandings](https://www.kaggle.com/competitions/map-charting-student-math-misunderstandings)

---

## Models Used

This project utilizes transformer-based Large Language Models for contextual understanding and misconception prediction.

### Qwen3

Used for advanced reasoning and semantic understanding of student responses.

### GLM-4

Used for deep contextual analysis and misconception classification.

The final predictions are generated through multi-model inference and ranking strategies.

---

## Features

* NLP-based misconception detection
* Transformer-powered text understanding
* Multi-model inference pipeline
* Contextual classification of student reasoning
* Automated prediction generation
* Ranking-based output evaluation

---

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Pandas
* NumPy
* Kaggle Notebook Environment

---

## Project Workflow

1. Load dataset
2. Preprocess student explanations
3. Tokenize text inputs
4. Run inference using transformer models
5. Generate misconception predictions
6. Rank predictions and create submission file

---

## Repository Structure

```bash
├── data/
├── notebooks/
├── map_modules/
├── prepare_test.py
├── test.py
├── README.md
└── requirements.txt
```

---

## Evaluation Metrics

The project uses standard NLP evaluation metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* MAP@K

These metrics help evaluate how effectively the system identifies and ranks misconceptions.

---

## Future Improvements

* Real-time educational feedback system
* Multilingual misconception detection
* Explainable AI for educational insights
* Integration with online learning platforms
* Improved fine-tuning for educational NLP tasks

---

## Conclusion

This project demonstrates how Artificial Intelligence and Natural Language Processing can be applied in education to better understand student reasoning and identify conceptual learning gaps. By moving beyond simple right-or-wrong evaluation, the system aims to support more personalized, adaptive, and intelligent learning experiences.

---

## Author

Developed as part of an NLP and Educational AI project focused on automated mathematical misconception detection using Large Language Models.

