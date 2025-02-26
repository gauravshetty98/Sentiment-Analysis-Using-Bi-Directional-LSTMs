# LSTM Sentiment Analysis - Block Diagram

## Overview
This project performs **Sentiment Analysis on IMDB Reviews** using **Bi-directional LSTMs**.


## Steps in the Pipeline

1. **Data Collection** 📥
   - IMDB dataset is used for training and testing.

2. **Text Preprocessing** ✂️
   - Tokenization, stopword removal, and lemmatization.
   - Converts text into numerical format using **one-hot encoding**.
   - Sequences are padded to ensure uniform input size.

3. **Data Splitting** 🔄
   - The dataset is divided into **training** and **testing** sets.

4. **Embedding Layer** 🔢
   - Converts words into numerical representations for input to the LSTM model.

5. **Bi-directional LSTM** 🧠
   - Processes text sequences forward and backward to understand context.

6. **Dropout Layer** ⚠️
   - Helps in **regularization** to prevent overfitting.

7. **Dense Layer** 🎯
   - Final prediction layer that classifies sentiment (positive/negative).

8. **Model Evaluation** 📊
   - Evaluates **accuracy, loss, recall, and precision**.

## Repository Structure
```
📂 Project Folder
 ├── 📄 LSTM_Model_Report.ipynb    # Jupyter notebook with full model implementation
 ├── 📄 README.md                  # Project documentation
```

For further details, refer to the **Jupyter Notebook** in this repository. 🚀

