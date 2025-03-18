#Sequence Prediction Using Deep Learning Techniques
This project focuses on predicting sequences using advanced deep learning methods, specifically Long Short-Term Memory (LSTM) networks. The goal is to predict the sequence of file blocks accessed by client applications in a distributed file system environment. We utilized synthetic log data containing file and block access patterns, preprocessed the data, and trained an LSTM model to forecast the block sequences based on the frequency of block usage.
Key highlights:
Tech Stack: Python, Pandas, NumPy, Scikit-Learn, Keras
Model: LSTM (a type of Recurrent Neural Network)
Dataset: 100,000 synthetic log entries simulating distributed file systems (10 racks, 10 data nodes per rack, 10,000 files, and 1,000 blocks)
