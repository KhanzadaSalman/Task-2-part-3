# Task 2 part 3: News Topic Classifier Using BERT

## 📌 Problem Statement
The objective of this task is to fine-tune a transformer model to classify news headlines into four distinct categories: World, Sports, Business, and Sci/Tech. We utilized the **AG News** dataset and a pre-trained **DistilBERT** model.

## ⚙️ Methodology
1.  **Data Loading:** Loaded the AG News dataset from Hugging Face.
2.  **Preprocessing:** Tokenized text using `DistilBertTokenizerFast`.
3.  **Model:** Used `DistilBertForSequenceClassification` (a lighter version of BERT).
4.  **Fine-Tuning:** Trained the model using the Hugging Face `Trainer` API.
    * *Note: To ensure timely completion within the internship timeframe, the model was trained on a demonstration subset of the data.*

## 📊 Key Results
* **Model Used:** DistilBERT (Base Uncased)
* **Optimization:** Disabled external logging (WandB) and reduced batch sizes for speed.
* **Outcome:** The pipeline runs end-to-end, demonstrating the complete transfer learning workflow.

## 🛠 Tools Used
* Python
* Hugging Face Transformers & Datasets
* PyTorch
* Scikit-learn
