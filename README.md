# 🛍️ Online Shoppers' Purchasing Intention (Decision Tree & Pruning)

This project is a classification study developed to analyze the behavioral and seasonal data of e-commerce website visitors to predict whether they will complete a purchase.

## 🎯 Project Objective
To assist in making strategic decisions to increase conversion rates by analyzing metrics such as the time users spend on cart pages, page view counts, bounce rates, and the impact of special occasions.

## 🧠 Model Development and Tree Pruning Analysis
Decision Trees are naturally prone to overfitting the training data. In this project, Tree Pruning (Pre/Post-Pruning) processes were analyzed to prevent the model from memorizing the training data:
* **Before Pruning:** When the model was left unconstrained, it showed high performance on the training data, but its generalization capability on the test data decreased (overfitting).
* **After Pruning:** By optimizing hyperparameters such as `max_depth` and `min_samples_split`, the tree was pruned to achieve a more balanced and stable model.

## 🛠️ Technologies Used
* **Programming Language:** Python
* **Libraries:** Scikit-Learn (DecisionTreeClassifier, plot_tree), Pandas, NumPy, Matplotlib, Seaborn
* **Performance Evaluation:** Using `ConfusionMatrixDisplay`, the confusion matrices before and after pruning were visualized side-by-side to clearly illustrate the adjustments in the model's performance.

## 🚀 Running the Project Locally
```bash
git clone https://github.com/BerkayYLMZ5353/online-shoppers-intention-dt.git
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook DecisionTree_Odev.ipynb
```
```
