# Preparing a Dataset for fine-tuning & 
# Traditional fine-tuning 

This project uses the **Cleveland Clinic Patients Feedback** dataset to fine-tune a BERT-base model for 3-class sentiment classification (Positive, Neutral, Negative).

## 🚀 Features
- **Data Augmentation:** Uses NLTK WordNet for synonym replacement to balance the dataset.
- **Preprocessing:** Custom regex cleaning and automated label mapping.
- **Model:** Fine-tuned `bert-base-uncased` using the Hugging Face `Trainer` API.

## 🛠️ Setup
1. **Kaggle API:** Ensure you have your `KAGGE_USERNAME` and `KAGGLE_KEY` set in your environment.
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
