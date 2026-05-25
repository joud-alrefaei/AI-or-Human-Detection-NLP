# AI vs Human Text Detection for Arabic Language (NLP Project)

## 🎯 Project Goal
The goal of this project is to build a Natural Language Processing (NLP) system that distinguishes between AI-generated text and human-written text in Arabic. 

We explore both traditional machine learning and transformer-based models to compare their performance in detecting text origin.

## 📊 Dataset
The dataset consists of Arabic text samples labeled as either:
- Human-written text
- AI-generated text

## 🧠 Methods and Models Used

### Traditional Machine Learning Models:
- Support Vector Machine (SVM)
- Naive Bayes (NB)
- Logistic Regression

### Transformer-Based Models:
- AraBERT
- MARBERT

## ⚙️ Workflow
- Data preprocessing and cleaning
- Text normalization for Arabic language
- Feature extraction (TF-IDF / embeddings)
- Training traditional ML models
- Fine-tuning transformer models
- Evaluating and comparing performance

## 📈 Results
The models were evaluated to classify whether a text is AI-generated or human-written. 
Transformer-based models (AraBERT and MARBERT) performed better in capturing contextual meaning compared to traditional models.

## 🚀 Future Work
- Improve classification accuracy using larger datasets
- Experiment with more advanced transformer models
- Build a web application for real-time detection
- Add explainability methods to understand model decisions

## 🔗 Notebook
You can view the full implementation here:
https://colab.research.google.com/drive/1UzbJHQ7VH2W6THM8gRMA2ds1Qof1iuqg?usp=sharing#scrollTo=l1-AVUsoR4c7
