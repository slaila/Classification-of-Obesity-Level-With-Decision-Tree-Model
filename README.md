# Classification of Obesity Level with Decision Tree Model

## 📌 Project Overview

This project applies a **Decision Tree Classifier** to predict obesity
levels based on demographic, lifestyle, and health-related factors. The
objective is to explore how machine learning can help identify obesity
risk categories and provide a baseline for further predictive modeling.

## 📂 Dataset

The dataset consists of **2,111 records** with various demographic and
lifestyle attributes.\
The target label is **NObeyesdad**, which represents different
categories of obesity levels:\
- Underweight\
- Normal Weight\
- Overweight (Level I, Level II)\
- Obesity (Type I, Type II, Type III)

## 🛠 Methodology

1.  **Data Preprocessing**
    -   Checked and handled missing values\
    -   Encoded categorical variables\
    -   Normalized numerical features where needed
2.  **Model Development**
    -   Implemented a **Decision Tree Classifier**\
    -   Performed hyperparameter tuning to optimize performance
3.  **Evaluation**
    -   Metrics: Accuracy, Precision, Recall, F1-score\
    -   Confusion Matrix for multi-class classification analysis

## 📊 Results

-   The **Decision Tree model** achieved an accuracy of **around 85%**
    on the test set.\
-   The model effectively classified individuals into multiple **obesity
    categories**.\
-   **Dietary patterns, physical activity, and family history** were
    among the most influential predictors.\
-   This project shows that Decision Trees can serve as an interpretable
    baseline for obesity classification tasks.

## 🚀 How to Run

1.  Clone the repository:

    ``` bash
    git clone https://github.com/username/obesity-decision-tree.git
    cd obesity-decision-tree
    ```

2.  Install dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

3.  Run the notebook:

    ``` bash
    jupyter notebook Classification_of_Obesity_Level_With_Decision_Tree_Model.ipynb
    ```

## 📦 Dependencies

-   Python 3.x\
-   Jupyter Notebook\
-   pandas\
-   numpy\
-   scikit-learn\
-   matplotlib / seaborn

## ✨ Future Work

-   Compare performance with ensemble methods (Random Forest, XGBoost).\
-   Enhance feature engineering for improved accuracy.\
-   Deploy as a web-based tool for practical use.
