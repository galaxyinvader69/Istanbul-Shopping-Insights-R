# Istanbul Shopping Insights-R

## *Project Overview*

*Team:* Third Team

*Team Members:*
- Charan Reddy Tamma
- Pranideep Reddy Meka
- Rakesh Venigalla
- Phani Vishnu Addepalli

This project focuses on analyzing consumer behavior and shopping trends using the *Istanbul Shopping Dataset*, which includes 99,458 records from ten malls in Istanbul between 2021 and 2023. The dataset provides key insights into consumer demographics, shopping patterns, payment methods, and more. By performing exploratory data analysis (EDA) and applying statistical models, we aim to uncover patterns in the dataset and forecast future trends in the retail landscape.

---

## *Dataset Description*

The *Istanbul Shopping Dataset* includes the following attributes:

- *invoice_no*: Unique identifier for each invoice (combination of 'I' and a 6-digit number).
- *customer_id*: Unique identifier for each customer (combination of 'C' and a 6-digit number).
- *gender*: Customer’s gender.
- *age*: Age of the customer.
- *category*: Product category purchased.
- *quantity*: Quantity of items purchased.
- *Price in numbers*: Unit price of the product in Turkish Liras (TL).
- *payment_method*: Method of payment (Cash, Credit Card, or Debit Card).
- *invoice_date*: Date when the transaction occurred.
- *shopping_mall*: Name of the mall where the transaction was made.

The dataset offers a wealth of information, making it an excellent resource for understanding consumer behaviors, purchasing trends, and mall-related insights.

---

## *Project Goal*

The goal of this project is to create robust regression models to answer SMART questions based on the dataset and provide actionable insights for economic strategists in shopping malls. The models will predict future trends and explain historical consumer behaviors, focusing on retail payments, shopping habits, and the impact of demographics on purchasing decisions.

---

## *SMART Questions*

In this project, we aim to answer the following SMART questions:

1. *Does the total purchase amount affect the payment method?*
2. *Is there a correlation between a customer's age and gender with their shopping behavior?*
3. *Does the shopping mall location affect the frequency of purchases?*
4. *Are certain product categories associated with higher total purchase amounts than others?*
---

## Key Findings
- **Demographic Factors**: Age and gender appear to have **minimal impact** on purchasing behavior, with **product category** being the dominant factor.
- **Product Categories**: Different product categories show **distinctive effects** on the total purchase amount, providing insights into **consumer preferences**.
- **Reliability**: The results emphasize that **consumer preferences** are more influential in determining spending patterns than personal demographics.

---

## *Methodology*

1. *Exploratory Data Analysis (EDA)*: The first phase of the project involved thorough data exploration, including data cleaning, visualization, and statistical analysis to uncover patterns and correlations.
2. *Regression Modeling*: Based on the insights from the EDA, we built regression models to analyze the relationship between various factors such as purchase amount, payment method, demographics, and shopping habits.
3. *Forecasting*: Using the developed models, we made predictions about future trends in shopping behavior, such as shifts in payment method preferences and consumer spending.

---

## Areas for Improvement
While the study revealed important insights, several improvements could be made:
- Investigate the relationships between **age** and **product categories** to explore deeper insights into consumer behavior.
- Consider external factors such as **economic conditions** or **promotional events** to improve the model’s accuracy.
- Incorporate **consumer preferences** or **marketing effects** into the analysis for a more comprehensive understanding.

---

## Conclusion
Our analysis highlights that **product preferences** are the primary determinant of consumer spending in Istanbul’s malls, while **age** and **gender** have a **minimal impact**. This finding suggests that marketing and sales strategies should focus more on **product categorization** and **consumer choice patterns** rather than demographic targeting.

---

## *Installation and Setup*

To run the project locally, follow these steps:

1. Clone this repository:
```bash
   git clone https://github.com/Rakeshvenigalla/Istanbul-Shopping-Insights-R.git
```
2. Navigate to the project directory:
  ```bash
  cd Istanbul-Shopping-Insights-R
  ```
3. Install the necessary R packages:
  ```bash
  install.packages(c("ggplot2", "dplyr", "caret", "randomForest", "lmtest"))
  ```
4. Load the dataset and start running the analysis using RStudio or an R environment.

---

## References

1. **Customer Shopping Dataset - Retail Sales Data**. Kaggle. Retrieved from [Kaggle](https://www.kaggle.com/code/mostafaabdelbadie/customer-shopping-dataset-retail-sales-data-eda/input)

2. **About Linear Regression**. IBM. Retrieved from [IBM](https://www.ibm.com/topics/linear-regression#:~:text=Resources-,What%20is%20linear%20regression%3F,is%20called%20the%20independent%20variable.)

3. **Highly Effective Questions are SMART Questions**. Medium. Retrieved from [Medium](https://emkautsar.medium.com/highly-effective-questions-are-smart-questions-59040efea480)

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
