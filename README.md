### Logistic Regression Project: OLS Method vs. Sklearn Linear Model on 20 Newsgroups and Mushroom Datasets

### Overview:
This project compares the performance of logistic regression models for multiple class and binary classification problems using two datasets: the 20 Newsgroups dataset (for multi-class classification) and the Mushroom dataset (for binary classification). We implemented logistic regression using two methods: Ordinary Least Squares (OLS) and Sklearn's LinearModel. The goal was to analyze the accuracy, performance, and efficiency of both methods on different datasets.

### Result:
1. 20 Newsgroups Dataset (Multi-Class Classification): Both OLS and Sklearn’s logistic regression provided similar results in terms of accuracy and classification performance, with Sklearn’s model generally being more robust and quicker in training. Sklearn’s implementation likely benefited from optimized algorithms and regularization techniques, leading to slightly better performance, especially in terms of handling larger datasets.

2. Mushroom Dataset (Binary Classification): For the binary classification task, both methods again yielded similar results. However, Sklearn's model showed better handling of the dataset in terms of stability and speed. The accuracy was high for both models, but OLS required more careful tuning, and the lack of regularization in OLS might have led to slight overfitting.

### Conclusion:
In both datasets, the performance between the OLS method and Sklearn’s logistic regression model was comparable. Sklearn’s model was consistently more efficient, stable, and faster, while OLS, though effective, lacked some optimizations and regularization. Overall, while OLS can work for logistic regression, Sklearn’s linear model is recommended for practical use, particularly for larger datasets or when regularization is needed.







