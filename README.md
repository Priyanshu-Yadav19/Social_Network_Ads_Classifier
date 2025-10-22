# 🧠 Social Network Ads Classifier

This project demonstrates how to build and evaluate **Decision Tree** and **Random Forest** models to predict whether a user will purchase a product based on their **Age**, **Gender**, and **Estimated Salary**.

It includes a complete machine learning pipeline: data exploration, preprocessing, model training, evaluation, and visualization.

---

## 📁 Dataset

- **File Used**: `Social_Network_Ads.csv`
- **Target Variable**: `Purchased` (0 = No, 1 = Yes)

---

## 🚀 Project Flow

1. **Data Exploration**
   - `.info()`, `.describe()`, null checks
   - Pairplot visualization with `seaborn`

2. **Data Preprocessing**
   - Dropped irrelevant columns (`User ID`)
   - One-hot encoded `Gender`
   - Train-test split

3. **Model Training**
   - Trained a **Decision Tree Classifier**
   - Trained a **Random Forest Classifier**

4. **Evaluation**
   - Accuracy, confusion matrix, classification report
   - ROC curve and AUC comparison
   - Feature importance visualization

5. **Conclusion**
   - Random Forest outperformed Decision Tree in accuracy and stability
   - Age and Estimated Salary were the most predictive features

---

## 📊 Visualizations

- Pairplot of features by class
- Decision Tree structure
- Feature importance bar chart
- ROC curves for both models

---

## 🛠️ Libraries Used

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn

To install dependencies:

pip install -r requirements.txt

💡 How to Run

Clone the repo or download the notebook

Place Social_Network_Ads.csv in the same directory

Open the notebook in Jupyter or VS Code

Run all cells sequentially

📌 Author

Priyanshu Yadav Asipring ML Engineer | Focused on real-world, user-facing ML appsGitHub Profile

📎 License

This project is open-source and free to use for educational purposes.


---

### ✅ What to Do Next

1. Save this as `README.md` in your GitHub repo.
2. Upload your notebook and `requirements.txt`.
3. Add a short project description in the GitHub sidebar (e.g., “Predicting purchase behavior using Decision Tree and Random Forest”).

Let me know when it’s live — I’d love to review your repo and help you polish it even more!
