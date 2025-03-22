# Vectorized-Linear-Regression


This project applies **Multiple Linear Regression** to predict **insurance charges** based on features such as age, sex, BMI, number of children, smoking status, and region. It aims to demonstrate how linear regression can model real-world, multivariate relationships using a healthcare dataset.

## 📌 Objectives

- Load and explore the insurance dataset
- Preprocess categorical and numerical features
- Train a multiple linear regression model to predict medical charges
- Evaluate the model's performance
- Visualize feature relationships

## 📂 Dataset

The dataset contains the following features:
- `age`: Age of primary beneficiary
- `sex`: Insurance contractor gender
- `bmi`: Body mass index
- `children`: Number of children covered by health insurance
- `smoker`: Smoking status (yes/no)
- `region`: Residential area
- `charges`: Individual medical costs billed by health insurance

Source: [Insurance Dataset on Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 🧠 Workflow

1. **Data Loading**: Read the CSV dataset into a Pandas DataFrame.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized feature distributions and relationships.
   - Checked correlation with the target variable `charges`.
3. **Preprocessing**:
   - Converted categorical variables using one-hot encoding.
4. **Model Training**:
   - Trained a Multiple Linear Regression model using Scikit-learn.
5. **Evaluation**:
   - Used R² score and Mean Squared Error to assess model accuracy.

## 📈 Key Insights

- Smoking status and BMI have a strong impact on medical charges.
- Age and number of children also show meaningful correlation with cost.

## 🚀 Future Enhancements

- Experiment with polynomial regression or regularization (Ridge/Lasso)
- Compare performance with Decision Trees or Random Forests
- Perform hyperparameter tuning and cross-validation

## 💡 Author

**Lohitha Mahesh**  
[Portfolio](https://www.lohitha.org/) | [LinkedIn](https://www.linkedin.com/in/lohithamahesh/) | [GitHub](https://github.com/lohitha-17)

---

Feel free to fork, star ⭐, and contribute to this project!
