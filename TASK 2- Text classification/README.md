# Task 2: Text Classification 🎯  

## 📌 **Description**  
This task involves **classifying texts into categories** using four different **machine learning algorithms**:  
1. **Multinomial Naïve Bayes**  
2. **Support Vector Machine (SVM)**  
3. **Rocchio Classifier**  
4. **K-Nearest Neighbors (KNN)**  

The goal is to train classifiers to distinguish between relevant and non-relevant texts based on linguistic features.

---

## 🎯 **Objective**  
- Perform **text classification** using machine learning models.  
- Apply **10-fold cross-validation** for robust evaluation.  
- Compare model performances using accuracy, precision, recall, and F1-score.  

---

## 📊 **Results**  

| Model | Accuracy | Precision | Recall | F1-Score |
|------------|----------|------------|--------|-----------|
| **Naïve Bayes** | 90.78% | 91.61% | 90.62% | 90.63% |
| **SVM** | 89.78% | 90.12% | 89.58% | 89.49% |
| **Rocchio** | 87.56% | 87.98% | 87.50% | 87.38% |
| **KNN** | 78.11% | 81.69% | 78.12% | 77.04% |

📌 **Key Takeaways:**  
- **Naïve Bayes performed the best**, suggesting that a probabilistic approach is most effective for this dataset.  
- **KNN struggled** due to high-dimensional text data, as it does not perform well with sparse vectors.  
- **SVM and Rocchio achieved reasonable results**, with SVM being slightly better.  

---

## 📂 **Files**  
- 📜 `Text_Classification.ipynb` – Jupyter Notebook containing the full classification analysis.  
- 📄 `stop_words_english.txt` – List of stop words used for filtering.  

---

## 🚀 **Usage**  
Run the notebook with:  
```bash
jupyter notebook Text_Classification.ipynb
