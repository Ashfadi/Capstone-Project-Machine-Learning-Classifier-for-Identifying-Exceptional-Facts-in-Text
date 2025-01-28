# 🚀 Exceptional Fact Classifier

This repository contains a machine learning-based **Exceptional Fact Classifier** developed as part of a capstone project. The goal is to automate the identification of **exceptional facts** in textual data using advanced Natural Language Processing (NLP) techniques.

---

## 📌 Key Features
- **Definition of Exceptional Facts**: Facts that highlight rare characteristics of an entity within a context (e.g., "Denzel Washington followed Sidney Poitier as only the second black to win the Best Actor award").
- **Keyword-based Sentence Extraction**: Extracted sentences from Wikipedia using 55 pre-defined keywords.
- **Human Annotation**: Annotated 288 sentences as "Yes" (exceptional) or "No" (non-exceptional).
- **DistilBERT Classifier**:
  - Built using **DistilBERT**, a lightweight version of BERT, ideal for smaller datasets.
  - Achieved **77.26% accuracy**, with balanced precision and recall.

---

## 🛠 Methodology
1. **Data Preparation**:
   - Extracted sentences using a keyword-based approach from Wikipedia.
   - Annotated sentences into two classes: "Yes" (exceptional) and "No" (non-exceptional).

2. **Classifier Development**:
   - Leveraged **DistilBERT**, a lightweight NLP model.
   - Used stratified 5-fold cross-validation for robust evaluation.

3. **Evaluation**:
   - Accuracy: **77.26%**.
   - Precision: **76.47%**.
   - Recall: **76.32%**.
   - F1 Score: **76.10%**.

---

## 📊 Results
- **Key Insights**:
  - Exceptional facts are challenging to classify due to their rarity and nuanced context.
  - The model successfully balances precision and recall, making it suitable for real-world applications.

---

## 📈 Applications
The exceptional fact classifier can be applied across various fields:
- **Journalism**: Highlight rare or unique details in news articles.
- **Research**: Automate the extraction of novel findings in academic papers.
- **Data Analysis**: Identify outliers or key patterns in large datasets.

---

## 🔥 Future Prospects
1. Expand the dataset with more diverse and complex examples.
2. Implement fine-tuning of hyperparameters for improved performance.
3. Test the model's applicability across other domains (e.g., healthcare, finance).
4. Collaborate with annotators to reduce subjective bias in labeling.

---

## 📝 References
- **DistilBERT**: Hugging Face's lightweight version of BERT for NLP tasks.
- Related work on text classification and exceptional fact extraction.

---

## 📬 Contact
**Author**: Alishbah Fahad  

This repository is part of the capstone project supervised by **Dr. Chengkai Li**, University of Texas, Arlington.
