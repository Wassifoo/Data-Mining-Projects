# Data Mining Projects

This repository contains all the data mining projects I have completed so far. Each project focuses on different data analysis and machine learning techniques to address specific problems.

## Table of Contents

- [Regression Project](#regression-project)
- [Classification Project](#classification-project)
- [Convolutional Neural Network Project](#convolutional-neural-network-project)
- [Markov Model](#markov-model)
- [License](#license)

## Regression Project

### Overview

In the Regression Project, I applied a multiple linear regression model to predict car prices based on several characteristics. The main steps included data cleaning, categorical reduction, feature selection, encoding, and model evaluation.

### Details

- **Data Cleaning:** Addressed issues like converting numerical columns loaded as objects and resolving inconsistencies in categorical columns.
- **Categorical Reduction:** Simplified 'body' categories into main types: Sedan, Coupe, Convertible, Hatchback, SUV, Minivan, Wagon, and Pickup Truck.
- **Feature Selection:** Chose factors such as mileage, condition, transmission type, and car make.
- **Categorical Encoding:** Applied suitable methods to transform categorical variables into numerical equivalents.
- **Regression Modeling:** Trained a multiple linear regression model and evaluated it using metrics like R-squared, mean squared error, and residual analysis.
- **Visualizations:** Provided insights through visualizations, including bar plots and box plots, to analyze trends and correlations.

### Key Insights

- Identified the most popular car brands and the impact of transmission type on selling prices.
- Analyzed the distribution of selling prices across different car makes and body types.
- Assessed correlations between odometer reading, car condition, and sale price.

## Classification Project

### Overview

In the Classification Project, I focused on predicting telecom customer churn using a classification algorithm. The project involved thorough data preprocessing, model training, and performance evaluation.

### Details

- **Data Preprocessing:** Addressed missing values and resolved inconsistencies to ensure data quality.
- **Churn Analysis:** Investigated voluntary churn to aid telecom companies in retention strategies.
- **Classification Algorithm:** Trained a classification model and provided insightful visualizations.
- **Key Queries:** Identified attributes correlated with churn, analyzed churn rates by payment methods, and examined churn intervals.

### Key Insights

- Highlighted significant predictors for churn and provided a detailed decision tree analysis.
- Evaluated model performance using metrics like precision, recall, and F1-score.

## Convolutional Neural Network Project

### Overview

This project aimed to predict customer churn using a Convolutional Neural Network (CNN) due to the complex nature of churn data and the need for a model capable of capturing intricate patterns.

### Details

- **Dataset:** Chose a customer churn dataset from the telecom industry with relevant features.
- **Attributes:** Focused on attributes most correlated with churn: paperless billing, monthly charges, senior citizen status, and payment method.
- **Sequential Neural Network:** Selected this architecture to capture temporal dependencies and sequential patterns in the data.
- **Performance Evaluation:** Achieved an accuracy of 80.77% with detailed analysis using precision, recall, and F1-score.

### Key Insights

- The model helps identify customers with high churn probability, allowing companies to take proactive measures.
- Addressed dataset imbalance and provided suggestions for model improvement.

## Markov Model

### Overview

In this project, I used a Markov Model to predict customer churn based on contract types. The analysis revealed how contract duration affects churn rates.

### Details

- **Dataset:** Selected a telecom customer churn dataset.
- **Contract Types:** Analyzed month-to-month, one-year, and two-year contracts.
- **Markov Model:** Developed a model to calculate transition probabilities between different states.

### Key Insights

- **Month-to-Month Contracts:** 42.71% probability of churning.
- **One-Year Contracts:** 11.27% probability of churning.
- **Two-Year Contracts:** 2.83% probability of churning.
- Longer contract periods correlate with lower churn rates.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to explore each project folder for more detailed documentation and code.

**Dataset Links:**
- [Telecommunications Industry Customer Churn Dataset](https://www.kaggle.com/datasets/aadityabansalcodes/telecommunications-industry-customer-churn-dataset)
