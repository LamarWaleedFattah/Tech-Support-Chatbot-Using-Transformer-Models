# 🤖 Tech-Support-Chatbot Using Transformer Models

## 📄 Project Description

This project explores the use of **pre-trained transformer models** for text classification in a technical support chatbot context. The models evaluated include:

- **BERT**
- **ALBERT**
- **RoBERTa**

The objective was to compare their performance on a shared dataset and assess their effectiveness in classifying support-related text inputs.

---

## 📊 Model Performance

| Model    | Accuracy | Notes                                                      |
|----------|----------|------------------------------------------------------------|
| BERT     | 0.94     | Delivered excellent results and high reliability           |
| ALBERT   | 0.93     | Slightly lower than BERT but still strong and consistent   |
| RoBERTa  | 0.03     | Significantly underperformed due to possible misconfiguration |

---

## 🚧 Challenges

- **RoBERTa’s Low Accuracy**  
  The most notable challenge was RoBERTa's poor performance. Possible causes include:
  - Misconfiguration of the model
  - Inconsistent data preprocessing (e.g., tokenization)
  - Incorrect hyperparameters

- **Data Preprocessing Consistency**  
  Preprocessing steps such as tokenization and special token handling need to be **uniform across all models**. Any mismatch can negatively affect performance.

- **Hyperparameter Tuning**  
  Key hyperparameters like learning rate, batch size, and training epochs need further tuning to optimize results, particularly for underperforming models.

---

## 🔮 Future Work

- Reinvestigate **RoBERTa’s configuration** and preprocessing pipeline  
- Apply **hyperparameter optimization** to all models (especially RoBERTa)  
- Experiment with **advanced preprocessing** and **fine-tuning techniques**  
- Evaluate performance on **additional datasets** to improve generalizability

---

## 📌 Summary

This project highlights the effectiveness of BERT-based models for text classification tasks in chatbot applications. Although RoBERTa underperformed, further investigation may help uncover and fix the root causes.

