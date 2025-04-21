🚫 Hate Speech Detection on Social Platforms

A deep learning-based project for detecting and classifying social media content into **neutral**, **offensive**, and **hate speech** categories. This project aims to support content moderation systems using advanced NLP and deep learning techniques.

🧠 Project Highlights

- 📊 **Problem Statement:** Identify and classify social media posts into one of three classes – neutral, offensive, and hate speech.
- 🔍 **Model Used:** Bidirectional LSTM (BiLSTM) neural network with strategic dropout regularization.
- 🧹 **Preprocessing:** Tokenization, normalization, embedding layers for contextual feature enhancement.
- 📈 **Performance:**
  - Training Accuracy: 97%
  - Validation Accuracy: 87%
  - ROC AUC: 0.94 (neutral), 0.91 (offensive), 0.89 (hate)

🧰 Tech Stack

- Python
- TensorFlow / Keras
- Natural Language Toolkit (NLTK)
- Scikit-learn
- Pandas, NumPy, Matplotlib, Seaborn

📂 Folder Structure

```
hate-speech-detection/
│
├── data/                # Dataset (cleaned & raw)
├── notebook/            # Jupyter notebooks
├── src/                 # Model and preprocessing scripts
├── results/             # Confusion matrices, ROC plots, etc.
├── README.md            # Project overview
├── requirements.txt     # Dependencies
└── report.pdf           # Research paper / final report (optional)
```

## 📊 Dataset

- Contains labeled tweets/posts with 3 classes:
  - `neutral`
  - `offensive`
  - `hate speech`

📌 Results

- Confusion Matrix shows high precision for offensive detection (~91%)
- Minor confusion between hate and offensive speech (16% cross-class error)
- ROC AUC confirms strong discrimination capability

📄 Research Paper

**Title:** *A Novel Deep Learning Approach for Hate Speech Detection on Social Platforms*  
**Presented at:** Code AI-25, MIT @ MAHE-Dubai  
**Publisher:** Springer (Scopus Indexed) 

🙋 Author

**Pavana M**  
📧 mpavana8603@gmail.com
🔗 [LinkedIn](www.linkedin.com/in/pavana-m-668663292) | [GitHub](https://github.com/pavana86))
