
# KNN Classification on Iris Dataset (Task 6)

## Objective
Implement K-Nearest Neighbors (KNN) algorithm on the Iris Species dataset to understand instance-based learning, K selection, normalization, and classification evaluation.

This project is part of **AI & ML Internship – Task 6**.

---

## What You’ll Learn
- KNN working principle
- Feature normalization
- Choosing optimal K
- Confusion Matrix & Accuracy
- Decision Boundary visualization
- Multi-class classification

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Files Included
- `KNN_Iris_Task6.ipynb` – Main Jupyter Notebook
- `README.md` – Project documentation

---

## Steps Performed

1. Loaded Iris dataset from sklearn
2. Applied StandardScaler for normalization
3. Split data into train/test sets
4. Tested K values from 1–10 (Elbow Method)
5. Selected K = 5
6. Trained KNN classifier
7. Evaluated using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
8. Visualized decision boundaries using first two features

---

## Results

- High classification accuracy achieved
- Optimal K found using accuracy curve
- Clear separation between Iris species
- Normalization significantly improved performance

---

## Output Visualizations

- K vs Accuracy graph
- Confusion Matrix
- Decision Boundary plot

---

## Conclusion

KNN performed effectively on the Iris dataset after feature scaling. Selecting the correct K is crucial for avoiding overfitting or underfitting. This project demonstrates practical implementation of instance-based learning.

  

---

If you found this helpful, don’t forget to star the repo!
