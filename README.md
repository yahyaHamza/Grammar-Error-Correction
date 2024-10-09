# Grammar Error Correction
This project is developed as part of the NLP course and focuses on building a Grammar Error Correction system. The system is designed to identify and correct grammatical errors in sentences, leveraging deep learning techniques and a carefully curated dataset.
## Table of Contents
- Overview
- Dataset
- Data Preprocessing
- Model Architecture
- Training
- Inference
- Graphical User Interface (GUI)
## Dataset
The dataset for this project is sourced from C4 (Colossal Clean Crawled Corpus), a large-scale dataset provided by Google. We selected 2 million samples for training the model.
- Source: Google's C4 Dataset
- Size: 2 million examples
## Data Preprocessing
The preprocessing pipeline includes:

1- Data Cleaning: Removing special characters, extra whitespaces, and irrelevant data.

2- Tokenization: Splitting sentences into tokens and preparing them for model input.

3- Padding: Ensuring sentence lengths are consistent for the LSTM model.
