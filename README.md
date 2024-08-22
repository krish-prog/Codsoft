Sales Prediction Project
Overview

This project focuses on predicting product sales based on advertising expenditures across various platforms, including TV, Radio, and Newspapers. By analyzing historical advertising data, we aim to forecast future sales and optimize advertising strategies.
Objective

The main objectives of this project are:

    To predict the amount of sales based on advertising spend on different platforms.
    To determine the optimal advertising expenditures that maximize sales.
    To visualize the relationship between advertising costs and sales to provide insights for decision-making.

Dataset

The dataset used in this project consists of the following columns:

    TV: Advertising expenditure on TV (in dollars).
    Radio: Advertising expenditure on Radio (in dollars).
    Newspaper: Advertising expenditure on Newspaper (in dollars).
    Sales: The amount of product sales (in units).

Project Steps
1. Data Analysis & Preprocessing

    Performed initial data exploration to understand the distribution and relationships within the data.
    Cleaned and preprocessed the data to ensure it was ready for modeling.

2. Feature Engineering

    Analyzed the impact of each advertising platform on sales.
    Created features that capture the relationship between advertising spend and sales.

3. Model Development

    Utilized a Linear Regression model to predict sales based on advertising expenditures.
    Fine-tuned the model to improve prediction accuracy.

4. Model Evaluation

    Evaluated the model's performance using metrics like R-squared (R²) and Mean Squared Error (MSE).
    Visualized the actual vs. predicted sales to assess model performance.

5. Optimization of Advertising Expenditures

    Calculated the optimal advertising spend for TV, Radio, and Newspaper to maximize sales.
    Optimal Advertising Expenditures:
        TV: $19,509,855.00
        Radio: $36,129,714.90
        Newspaper: $1,553,326.25

6. Visualization

    Plotted the relationship between actual and predicted sales.
    Visualized the impact of advertising expenditures on sales for each platform.

Results

The project successfully predicted sales based on advertising spend, identified optimal advertising expenditures, and provided visual insights into how advertising on different platforms influences sales.
Conclusion

This project demonstrates how data-driven approaches can optimize advertising strategies and improve sales forecasting. By leveraging machine learning techniques, businesses can make informed decisions about where to allocate their advertising budgets for maximum return on investment.
Technologies Used

    Python
    Pandas, NumPy
    Scikit-learn
    Matplotlib, Seaborn

How to Use

    Clone the repository.
    Install the necessary dependencies.
    Run the Jupyter notebook or Python scripts provided to replicate the analysis and visualizations.

Future Work

    Experiment with more advanced models like Random Forest or Gradient Boosting for improved prediction accuracy.
    Incorporate more features such as social media advertising or online campaigns to extend the analysis.
