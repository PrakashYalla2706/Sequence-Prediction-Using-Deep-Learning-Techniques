# 📊 Sequence Prediction Using Deep Learning Techniques

## 🚀 Overview
This project focuses on predicting sequences using advanced deep learning methods, specifically **Long Short-Term Memory (LSTM)** networks. The goal is to forecast the sequence of file blocks accessed by client applications in a distributed file system environment. By utilizing synthetic log data containing file and block access patterns, we preprocess the data and train an LSTM model to predict future block sequences based on the frequency of block usage.

---

## 🧠 Key Features
- **Deep Learning Model:** LSTM-based sequence prediction model
- **Dataset:** 100,000 synthetic log entries (10 racks, 10 data nodes per rack, 10,000 files, and 1,000 blocks)
- **Performance:**
  - **Accuracy:** 86.53%
  - **Precision:** 0.99
  - **Recall:** 0.85
- **Libraries Used:** Python, Pandas, NumPy, Scikit-Learn, Keras
- **Applications:** Natural Language Processing (NLP), speech recognition, anomaly detection, distributed systems behavior prediction

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-Learn
- Keras (TensorFlow backend)

---

## 📂 Dataset
The dataset consists of synthetic logs simulating access patterns in a distributed file system:
- **Files:** 10,000
- **Blocks:** 1,000
- **Racks:** 10
- **Data Nodes per Rack:** 10
- **Total Entries:** 100,000 log entries

---

## 📋 Methodology
1. **Data Collection:** Synthetic log generation using Medisyn technique.
2. **Preprocessing:**
   - Converted raw text file to CSV format.
   - Grouped and sorted data by Rack ID, Data Node ID, File ID.
   - Split block IDs into separate rows and calculated frequency.
   - Encoded File IDs and Block IDs using Label Encoding.
3. **Model Training:**
   - Built LSTM model.
   - Used Mean Squared Error (MSE) as the loss function.
   - Optimized using Adam optimizer.
4. **Evaluation Metrics:** Accuracy, Precision, Recall.

---




