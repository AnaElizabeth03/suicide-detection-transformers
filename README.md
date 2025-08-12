# 🧠 Suicide Detection Using Transformers

This project explores the use of transformer-based models (BERT, DistilBERT, and RoBERTa) for detecting suicidal ideation in text data using NLP techniques.

---

## 📁 Repository Structure

- `transformers_suicide_detection.ipynb`: Main Colab notebook containing the full pipeline: data preprocessing, training, evaluation, and result visualization.

---

## 📂 Dataset

The dataset used in this project is publicly available on Kaggle:

🔗 [**Suicide Watch Dataset**](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch)

- Contains Reddit posts labeled as `suicide` or `non-suicide`.
- Used for binary classification.
- Due to licensing and size restrictions, the dataset is **not included** in this repository.

---

## 🧠 Models Used

- `bert-base-uncased`
- `distilbert-base-uncased`
- `roberta-base`

All models are fine-tuned using the HuggingFace Transformers library.

---

## 📊 Key Features

- Balanced dataset: 5000 suicide + 5000 non-suicide examples.
- Transformer-based text classification.
- Custom metrics: accuracy, F1-score, confusion matrix, etc.
- Visual performance comparison across models.

