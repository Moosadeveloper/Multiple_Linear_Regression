# Multiple Linear Regression - Weight Prediction Model

## Project Overview

This project demonstrates **Multiple Linear Regression** using Python and Scikit-learn. The model predicts a person's **Weight** based on two input features:

* Height
* Gender

The model learns the relationship between these features and predicts the expected weight for new users.

---

## Dataset

The dataset contains the following columns:

* Height
* Gender
* Weight (Target)

### Features (Input)

* Height
* Gender

### Target (Output)

* Weight

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## Machine Learning Algorithm

* Multiple Linear Regression

---

## Project Workflow

1. Load the dataset.
2. Select Height and Gender as input features.
3. Select Weight as the target variable.
4. Split the dataset into training and testing sets.
5. Train the Multiple Linear Regression model.
6. Evaluate the model.
7. Predict weight using Height and Gender provided by the user.

---

## User Input

The program asks the user to enter:

* Height (Feet)
* Gender (Male/Female)

Example:

```text
Enter Height (Feet): 5.8
Enter Gender (Male/Female): Male
```

---

## Output

Example:

```text
Predicted Weight: 72.45 kg
```

---

## Project Structure

```text
Multiple_Linear_Regression/
│
├── Multiple Linear Regression.ipynb
├── README.md
└── weight-height.csv
```

---

## Conclusion

This project demonstrates how Multiple Linear Regression can be used to predict a person's weight using multiple input features. By considering both Height and Gender, the model provides more accurate predictions than using only a single feature.
