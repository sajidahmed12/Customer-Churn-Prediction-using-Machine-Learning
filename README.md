# Customer-Churn-Prediction-using-Machine-Learning
A fictional telco company that provided home phone and Internet services data  from customers in California  to predict their future churning rate with machine learning

<img src="https://atrium.ai/wp-content/uploads/2021/07/What-stops-customer-churn-Having-a-centralized-data-hub-does-and-heres-why.jpeg" />

Run this project in Google Colab.

<a target="_blank" href="https://colab.research.google.com/github/https://colab.research.google.com/drive/1SPGflw2zxkKzVcB_GK75khHFiwYczD4O?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


# Requirements 
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

# Dataset 
- Telco customer churn: IBM dataset [Download link](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset/code)
- Put the Extracted data into the ./data folder.

# Data Visualization 
![Image](images/Attribute_histogram_plots.png)

# Corelation Matrix 
![Corelation](images/correlation.png)


# Reuslt (Confusion Matrix)

## Random Forrenst Model 
![Corelation](images/Random_Forest_cm.png)

## Logistic Regression Model

![Corelation](images/Logistic_Regression_cm.png)

## Comprehensive summary 

From the model evaluation, we can see that out of 3 machine learning algorithms, Random Forest provides the highest accuracy for predicting the number of churn customers, **94%** after hyper-tuning the parameters. Before hyper-tuning, it was 92%. of the ROC and AUC scores; we can also interpret that both the **Decision Tree** and **Random forest** algorithms are efficient in predicting future churn values. We can state from the overall evaluation outcomes that **Random Forest** performs slightly better than the other two algorithms.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature using `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them using `git commit -m "Add your commit message here"`.
4. Push your changes to your fork using `git push origin feature/your-feature-name`.
5. Open a pull request to the main repository.
