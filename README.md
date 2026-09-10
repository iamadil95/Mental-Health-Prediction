# Mental Health Text Classification using Deep Learning 🧠

## 📌 Project Overview
This project is an advanced Natural Language Processing (NLP) deep learning model designed to classify text statements into distinct mental health states. It uses a **Bidirectional LSTM (BiLSTM)** neural network combined with **GloVe Word Embeddings** to understand the deep semantic context of user inputs.

This project was built to demonstrate how Artificial Intelligence can be used for early detection and routing in mental health crisis scenarios.

## 🎯 Target Classifications (6 Classes)
The model can accurately predict the following psychological states from raw text:
* Depression
* Anxiety
* Stress
* Bipolar
* Suicidal
* Normal

## 🛠️ Technology Stack
* **Language:** Python
* **Deep Learning Framework:** TensorFlow / Keras (Sequential API)
* **NLP Techniques:** Tokenization, Sequence Padding, Stanford GloVe Embeddings (100d)
* **Data Processing & ML:** Pandas, NumPy, Scikit-Learn
* **Visualizations:** Matplotlib, Seaborn

## 🚀 Key Features
1. **Pre-trained GloVe Integration:** Leverages 100-dimensional global word vectors for superior contextual understanding.
2. **BiLSTM Architecture:** Processes sequences in both directions (past and future context) for better pattern recognition.
3. **Overfitting Protection:** Implemented Dropout layers, Recurrent Dropouts, Batch Normalization, and Early Stopping.
4. **Live Inference Sandbox:** Contains an interactive script to test real-world sentences instantly.

## 📊 Results & Performance
* Achieved high classification accuracy (up to ~88%) on unseen testing data.
* Strong F1-Scores across all categories, proving high precision and recall, especially in critical classes like 'Suicidal' and 'Depression'.

## 👨‍💻 Author
**Md Adil Imam**  
**Rachit Ranjan Srivastava**
**Sumit Kumar**
**Ashish Kr Singh**
B.Tech in Computer Science and Engineering (AI & ML)
