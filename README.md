# 📊 Sentiment Analysis using RNN and LSTM

## 📌 Project Overview

This project focuses on **sentiment classification of text data** using deep learning models such as **Recurrent Neural Networks (RNN)** and **Long Short-Term Memory (LSTM)**.

The objective is to classify text (movie reviews) into **positive or negative sentiment** and compare the performance of both models.

---

## 📂 Dataset

* **IMDB Movie Reviews Dataset**
* Total samples: 50,000
* Labels: Positive / Negative

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn

---

## 🔄 Workflow

1. Load dataset
2. Data preprocessing

   * Tokenization
   * Sequence conversion
   * Padding
3. Model building

   * RNN Model
   * LSTM Model
4. Training models
5. Performance evaluation
6. Graph visualization

---

## 🧠 Models Used

### 🔹 RNN (Recurrent Neural Network)

* Handles sequential data
* Limited in capturing long-term dependencies

### 🔹 LSTM (Long Short-Term Memory)

* Uses memory cells and gates
* Better at capturing long-term dependencies

---

## 📈 Results

| Model | Accuracy |
| ----- | -------- |
| RNN   | ~80%     |
| LSTM  | ~88%     |

👉 LSTM performed better than RNN due to its ability to retain long-term information.

---

## 📊 Output

* Accuracy graph
* Training vs Validation performance
* Model comparison

---

## 📁 Project Structure

sentiment-analysis/
│── sentiment.ipynb
│── report.pdf
│── accuracy_graph.png
│── README.md

---

## 🚀 How to Run

1. Open the notebook in Google Colab or VS Code
2. Run all cells step-by-step
3. Observe outputs and graphs

---

## 📌 Conclusion

This project demonstrates how deep learning models can be used for sentiment analysis.
LSTM shows better performance compared to RNN for text classification tasks.

---

## 👨‍💻 Author

**Abhinav Gautam **

Roll No.2510940040

---
