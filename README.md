# 🚨 IPC Section Classifier for Indian Cyber Crime Reports 🇮🇳

An NLP-based text classification system that predicts relevant **Indian Penal Code (IPC)** sections from user-submitted cybercrime complaints. Developed as part of the **Smart India Hackathon (SIH)** using real-world datasets provided by government authorities.

## 🧠 Objective

Enable automated tagging of IPC sections based on the narrative of cybercrime complaints submitted to the **Indian Cyber Crime Portal**. This tool can assist law enforcement in faster triage and legal categorization.

## 📌 Example

**Input:**  
"He created a fake Instagram profile with my photos and sent obscene messages to my friends."

**Predicted Output:**  
- `IPC Section 354D – Cyberstalking`  
- `IPC Section 509 – Word or gesture intended to insult modesty of a woman`  
- `IT Act Section 66E – Violation of privacy`

---

## ✅ Project Highlights

- Developed during **Smart India Hackathon (SIH)** using official government-provided dataset.
- Multi-label classification pipeline trained on anonymized complaint text.
- Outputs relevant IPC and IT Act sections with confidence scores.

---

## 🧰 Tech Stack

- Python  
- scikit-learn, NLTK, spaCy  
- Pandas, NumPy  
- Flask (for deployment)  
- Jupyter Notebooks (for EDA and training)

---

## 📊 Model Pipeline

1. **Text Preprocessing**  
   (Lowercasing, stopword removal, lemmatization, tokenization)

2. **Feature Engineering**  
   - TF-IDF Vectorization  
   - Optional word embeddings for extended analysis

3. **Multi-label Classification**  
   - Logistic Regression  
   - Random Forest  
   - Support Vector Machine  
   - (BERT under experimental phase)

4. **Evaluation Metrics**  
   - Precision, Recall, F1-Score (Macro & Micro)  
   - Label-based accuracy


