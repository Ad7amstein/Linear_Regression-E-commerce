# [Linear Regression Project: E-Commerce](https://colab.research.google.com/github/Ad7amstein/Linear_Regression-E-commerce/blob/main/ecommerce.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ad7amstein/Linear_Regression-E-commerce/blob/main/ecommerce.ipynb)
## About
This project focuses on utilizing linear regression with gradient descent to predict the yearly amount spent by customers in an e-commerce store that offers both in-store style and clothing advice sessions. The dataset contains information about customers who engage in these sessions and subsequently make purchases either through a mobile app or website.
## [Dataset](https://www.kaggle.com/datasets/kolawale/focusing-on-mobile-app-or-website/data)
The dataset consists of various features including:

- **Avg. Session Length**: Average duration of the session.
- **Time on App**: Duration spent by the customer on the mobile app.
- **Time on Website**: Duration spent by the customer on the website.
- **Length of Membership**: Duration spent by the customer in the store during the session.
- **Yearly Amount Spent(Target)**: Total amount spent by the customer annually.

## Methodology
- **Linear Regression with Gradient Descent**: Implemented linear regression from scratch utilizing gradient descent to predict the yearly amount spent by customers based on the given features.
- **Normalization**: Applied feature normalization to accelerate the gradient descent process and ensure efficient model training.
- **Evaluation Metric**: Utilized the R-squared (r2_score) metric to assess the accuracy of the model's predictions.
- **Visualization**: Employed various plots and visualizations to gain insights into the data distribution, relationships between features, and the performance of the linear regression model.

## Usage
To utilize this project:

1. [Open in colab](https://colab.research.google.com/github/Ad7amstein/Linear_Regression-E-commerce/blob/main/ecommerce.ipynb)
2. Explore the generated plots and visualizations to analyze the data and model performance.
3. Experiment with different parameters and features to further enhance the model's accuracy.

## Dependencies
- Python 3.x
- NumPy
- Matplotlib
- pandas
- seaborn
