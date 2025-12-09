# Stress-Detection

This project builds a simple **text classifier** that labels text as:

- **Stress**
- **No Stress**

using a Naive Bayes model trained on a labelled dataset of text messages/posts.

---

## 1. Dataset

The notebook uses a file called **`stress.csv`** with at least:

- `text`: the raw text.
- `label`: numeric label (0 = No Stress, 1 = Stress).

Example:

| text                          | label |
|------------------------------|-------|
| I feel overwhelmed by exams  | 1     |
| Had a nice relaxing weekend  | 0     |

---

## 2. Requirements

Install the following packages:

```bash
pip install pandas numpy nltk matplotlib wordcloud scikit-learn
