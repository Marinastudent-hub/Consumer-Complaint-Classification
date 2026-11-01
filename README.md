# Consumer Complaint Classification

An NLP-based machine learning project that automatically classifies consumer complaints into five financial product categories using deep learning and Transformer models.

## Project Overview

The goal of this project is to build and compare different deep learning models for classifying consumer complaints based on their written narratives.

## Dataset

- **Source:** [Consumer Complaints Dataset – Kaggle](https://www.kaggle.com/datasets/shashwatwork/consume-complaints-dataset-fo-nlp)
- **Cleaned records:** 124,420
- **Training samples:** 99,536
- **Validation samples:** 12,442
- **Testing samples:** 12,442

## Complaint Categories

1. Credit Card
2. Credit Reporting
3. Debt Collection
4. Mortgages and Loans
5. Retail Banking

## Project Workflow

1. Data loading and exploration.
2. Data cleaning and preprocessing.
3. Duplicate handling and class distribution analysis.
4. Text tokenization and padding.
5. Deep learning model development.
6. Model training and evaluation.
7. Model comparison.
8. Prediction on new complaint text.
9. Interactive deployment using Gradio.

## Models Implemented

- SimpleRNN
- LSTM
- GRU
- Fine-Tuned DistilBERT

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- TensorFlow / Keras
- Hugging Face Transformers
- NLTK
- PyTorch
- Gradio
- Google Colab

## Interactive Demo

The project includes a Gradio interface where users can enter a new consumer complaint and receive:

- Predicted complaint category.
- Prediction confidence.
- Category probability scores.

## Repository Contents

- `Consumer_Complaint_Classification.ipynb` – Complete project notebook.

## How to Run

1. Open the notebook using Google Colab.
2. Run the notebook cells in order.
3. Load the dataset and train the models.
4. Launch the Gradio interface.
5. Enter a complaint to get a prediction.

## Screenshots

### Gradio Application
![Gradio Interface](Screenshot%202026-11-01%20224757.png)

### Model Predictions
![Prediction Example](Screenshot%202026-11-01%20224900.png)

### Complaint Classification Results
![Classification Results](Screenshot%202026-11-01%20224940.png)

### Additional Demo
![Demo](Screenshot%202026-11-01%20225027.png)
