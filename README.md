# 🧠 Spam Detection using Naive Bayes (from Scratch)

This project implements a **Spam/Ham classifier** using a **Multinomial Naive Bayes** algorithm written entirely from scratch — without using any built-in `scikit-learn` classifier.

---

## 🔍 What This Project Does

- Loads and vectorizes email/text data using `CountVectorizer`
- Implements Naive Bayes model manually:
  - Laplace smoothing(to handel unseen data)
  - Log-probability calculations
- Splits the data into training and testing sets
- Evaluates the model on unseen data
- Lets you input a custom message and classify it as **HAM** or **SPAM**
- Displays the most informative words per class

---

