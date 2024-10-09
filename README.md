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
- 
## Data Preprocessing
The preprocessing pipeline includes:

1- **Data Cleaning**: Removing special characters, extra whitespaces, and irrelevant data.

2- **Tokenization**: Splitting sentences into tokens and preparing them for model input.

3- **Padding**: Ensuring sentence lengths are consistent for the LSTM model.

## Model Architecture
We built a custom LSTM-based encoder-decoder model from scratch using TensorFlow. The model architecture includes:
- **Encoder**: Encodes the input sentence into a fixed-size context vector.
- **Decoder**: Decodes the context vector to predict the corrected sentence.

## Model Details:
- **Framework**: TensorFlow
- **Architecture**: LSTM Encoder-Decoder
- **Loss Function**: Cross-entropy
- **Optimizer**: Adam

## Training

## Inference
We implemented an inference function that takes an input sentence, tokenizes it, and passes it through the trained model to output the grammatically corrected sentence.
- **Input**: Sentence with grammatical errors.
- **Output**: Corrected sentence.

## Graphical User Interface (GUI)
To make the project more accessible, a simple GUI was built using Python's Tkinter. This GUI allows users to:
- Input sentences with grammatical errors.
- Get the corrected sentence as output.
- Display the corrected sentence on the interface.
