# 🧠 Mental Health Detection from Social Media Posts

## 🚀 Project Overview

This project focuses on building a manual deep learning model from scratch (without using high-level modules like `torch.nn` or `tf.keras`) to classify social media posts into mental health categories such as **depression**, **anxiety**, **stress**, and **neutral**. The model is trained and evaluated using a Reddit-based mental health dataset.

## 📁 Project Folder

This project is part of my [`deep-learning`](../) portfolio and is organized as follows:


## 📚 Technologies Used

- Python
- NumPy
- Matplotlib
- Manual PyTorch (only tensor ops, no `nn.Module`)
- Google Colab

## 🧠 Problem Statement

Mental health issues are often reflected in online behavior. This project attempts to automatically detect signs of depression, anxiety, or stress from Reddit posts using natural language processing and deep learning — built completely from scratch without using high-level libraries.

## 📊 Dataset Summary

- **Source**: Reddit Mental Health Dataset
- **Format**: CSV with `selftext` and `subreddit` fields
- **Preprocessing**:
  - Lowercasing, punctuation removal
  - Tokenization, vocabulary building
  - Text vectorization into padded sequences

## 🔧 Model Highlights

- Fully manual implementation (no use of `torch.nn`)
- Components implemented from scratch:
  - Embedding lookup
  - Forward propagation
  - Softmax and cross-entropy loss
  - Gradient calculation and weight updates
- Metrics:
  - Accuracy, Precision, Recall

## 📈 Results

| Metric     | Value (approx.) |
|------------|-----------------|
| Accuracy   | ~87%            |
| Precision  | ~86%            |
| Recall     | ~85%            |

> Metrics may vary slightly depending on run.

## 📉 Training Visualization

*(Add plots of training loss and accuracy here if available)*

## 📂 File Descriptions

| File                           | Description                                      |
|--------------------------------|--------------------------------------------------|
| `mental_health_detection.ipynb` | Google Colab notebook with code and explanations |
| `requirements.txt`            | Python package dependencies                      |
| `README.md`                   | Project documentation                            |

## 💡 Key Learnings

- Built a deep learning model without high-level APIs
- Understood the internals of backpropagation and weight updates
- Gained hands-on experience in text preprocessing and manual NLP modeling

## ▶️ Run in Google Colab

You can run the full project in Google Colab using the link below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/deep-learning/blob/main/mental-health-detection/mental_health_detection.ipynb)

*(Replace `your-username` with your actual GitHub username after upload.)*

## 📜 License

This project is open-sourced under the [MIT License](../../LICENSE).

---

