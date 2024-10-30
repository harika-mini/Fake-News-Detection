# Fake News Detection System

## Overview
The **Fake News Detection System** is an advanced machine learning application designed to accurately identify and classify news articles as either real or fake. By utilizing ensemble learning techniques, this project combines **Long Short-Term Memory (LSTM)** and **Bidirectional LSTM (BiLSTM)** models to achieve remarkable performance.

## Key Features
- **Ensemble Learning**: Leverages a combination of LSTM and BiLSTM models for enhanced predictive capabilities.
- **High Accuracy**: Achieves an impressive accuracy rate of **99.2%**, demonstrating the effectiveness of the implemented methodologies.
- **Data Preprocessing**: Incorporates essential data cleaning and preparation steps to ensure optimal model input.
- **Comprehensive Evaluation**: Implements a range of metrics, including accuracy, precision, recall, and F1-score, for thorough model assessment.

## Technical Details
- **Frameworks Used**:
  - **TensorFlow** and **Keras** for building and training the LSTM and BiLSTM models.
  - **Pandas** for data manipulation and analysis.
  - **NumPy** for numerical computations.
  
- **Dataset**: The model is trained on a curated dataset of news articles labeled as real or fake, sourced from diverse platforms.

- **Implementation Steps**:
  1. **Data Collection**: Compiled a comprehensive set of news articles for both training and testing.
  2. **Data Preprocessing**: Cleaned and tokenized text data, removed stop words, and applied stemming/lemmatization techniques.
  3. **Model Training**: Designed and trained the LSTM and BiLSTM models using the preprocessed data.
  4. **Model Evaluation**: Evaluated performance metrics using a holdout test set.

## Installation and Usage
To get started with the Fake News Detection System, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/harika-mini/FakeNewsDetection.git
   ```
2. Navigate into the project directory:

```bash
cd FakeNewsDetection
```
3. Install the required packages:
```bash
pip install -r requirements.txt
```
4.Run the application:
```bash
python main.py
```
## Conclusion
The Fake News Detection System illustrates the power of ensemble learning in natural language processing. By integrating LSTM and BiLSTM models, this application not only achieves high accuracy but also establishes a robust framework for future enhancements and research in fake news detection.
