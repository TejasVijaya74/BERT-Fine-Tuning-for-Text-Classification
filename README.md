# BERT Fine-Tuning for Text Classification

This project demonstrates fine-tuning a pre-trained BERT model for a text classification task using Hugging Face Transformers and PyTorch.

##  Objective
Build a text classification model by fine-tuning BERT on a real-world dataset and evaluate its performance using standard metrics.

##  Tech Stack
- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Jupyter Notebook

##  Dataset
A Kaggle dataset is used (e.g., IMDB / Twitter Sentiment / News Classification / Toxic Comments).

##  Pipeline
1. Data Preprocessing  
2. Train/Validation/Test Split  
3. Tokenization (`bert-base-uncased`)  
4. Model Training (BERT Fine-tuning)  
5. Evaluation (Accuracy, Precision, Recall, F1-score)  
6. Experiments & Comparison  

##  Model
- `bert-base-uncased`
- `AutoModelForSequenceClassification`
- Optimizer: AdamW  
- Learning Rate: 2e-5  

##  Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

##  Experiments
- Freeze BERT layers + train classifier  
- Fine-tune last layers of BERT  
- Compare performance  

##  Output
- Trained model  
- Performance metrics  
- Confusion matrix  
- Analysis of results  
