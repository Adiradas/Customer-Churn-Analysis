# Customer-Churn-Analysis
Bank Data

Let's elaborate on the entire README file for my customer churn analysis project in GitHub.

---

# Customer Churn Analysis for Bank Data

## Introduction

Customer churn analysis is a critical process for financial institutions like banks. It involves understanding and mitigating the loss of customers, which can significantly impact a bank's revenue and growth. In this project, we have conducted a comprehensive analysis of customer churn using Power BI on bank customer data. This README file provides a detailed overview of the data preparation, data modeling, and key insights generated during the analysis.

## Data Preparation

### 1. Renaming Column Names

One of the first steps in data preparation was renaming the column names. This was done to make the data more understandable and meaningful for visualization and analysis. Clear and descriptive column names facilitate a smoother workflow when creating visualizations.

### 2. Removing "Estimated Salary"

The "Estimated Salary" column was deemed unnecessary for our analysis and was removed from the dataset. This decision was made after careful consideration of the project's goals and the relevance of each column.

### 3. Adjusting Data Types

Proper data types are essential for accurate analysis and visualization. We meticulously reviewed the data types and applied relevant ones to each column. Here are the data type adjustments that were made:

- **Customer ID:**  a whole number
- **Credit Score:** a whole number
- **Country:** Kept as text
- **Gender:** Kept as text
- **Age:** Changed to a whole number
- **Tenure:** Changed to a whole number
- **Balance:** Changed to a fixed decimal
- **Product:** Changed to a whole number
- **Credit Card:** Changed to a text (1 was replaced with "Own," and 0 with "Not Owned")
- **Active:** Changed to a text (1 was replaced with "Active," and 0 with "Inactive")
- **Churn Status:** Changed to a text (1 was replaced with "Churned," and 0 with "Not Churned")

### 4. Creating a New "Product" Column

To enhance the dataset, we introduced a new column for "Product" by example. We assigned labels such as "Prod1," "Prod2," and so on. The original "Products" column was removed after this transformation.

### 5. Creating Categories

To facilitate analysis and visualization, we created categories for certain columns:

- **Age Group:** We categorized customers into different age groups using conditional columns.
- **Credit Score Group:** Similar to age groups, we created categories for credit scores.
- **Balance Range:** Account balances were categorized into specific ranges.

## Data Modeling

Effective data modeling is crucial for gaining meaningful insights. Here are the steps taken during data modeling:

- **Age Groups Arranged Ascendingly:** We arranged age groups in ascending order to better understand the age distribution.
- **Age Group ID:** We introduced an "Age Group ID" to represent ascending age groups. For instance, customers aged <20 were assigned ID 1, those aged 21-30 were assigned ID 2, and so on.
- **Credit Score and Balance Categories:** Similar ID assignments were made for credit scores and account balances.

## Insights

In the fascinating journey through our bank's customer churn analysis, we've uncovered some intriguing stories hidden within the data. These insights shed light on the behaviors and trends that define our customers' experiences.

### 1. The Tale of Product Churn

Our first discovery is a gripping tale of product preferences and churn rates. It appears that "Product 1" has been causing a stir, with a significantly higher churn rate compared to other products. This revelation prompts us to delve deeper, understanding why this product is pushing customers away and what actions we can take to improve their satisfaction.

### 2. The Enigma of Product 2

Product 2, on the other hand, holds a mystery of its own. Customers using this product and maintaining account balances between 1,000 and 10,000 seem to be slipping through our fingers, exhibiting a 100% churn rate. This riddle challenges us to investigate further, deciphering why these particular customers are leaving and how we can retain their loyalty.

### 3. Inactivity Unveiled

Hidden within our dataset is a silent majority - approximately 51.5% of our customers are inactive. Their accounts lie dormant, waiting for a spark of engagement. We must embark on a mission to awaken these customers, rekindling their interest in our services.

### 4. The Gender Divide

A story of numbers unfolds as we observe the gender distribution among our customers. Men outnumber women in our dataset. This statistic piques our curiosity, prompting us to explore whether this gender divide affects churn rates and what strategies we can employ to create gender-inclusive banking experiences.

### 5. The Ages of Churn

The narrative takes a twist as we explore the age-related aspect of churn. Customers aged between 51 and 60 have emerged as central characters in this story, with a churn rate of around 60%. We must investigate what challenges this age group faces and tailor our offerings to better suit their needs.

### 6. The Credit Score Saga

Credit scores play a significant role in our tale. Customers with credit scores below 400 are more likely to churn. This subplot encourages us to examine the financial health of our customers and provide resources to help them improve their creditworthiness.

### 7. The Balance Conundrum

Finally, our journey leads us to a pivotal chapter – the balance-related churn. Customers with account balances ranging from 1,000 to 10,000 stand out with a higher churn rate. This revelation sparks a quest to understand why these balances are causing disquiet and how we can secure their trust.

In conclusion, our analysis is not just about numbers; it's about weaving stories from data. These stories guide us towards understanding customer behavior, addressing pain points, and crafting personalized strategies for customer retention. Our mission is to turn these insights into action, ensuring that each customer's story with our bank has a happy ending.

---

These insights offer valuable information to the bank for crafting targeted strategies to reduce customer churn, enhance customer retention, and optimize business operations.

---

This comprehensive README provides an in-depth overview of the customer churn analysis project. For detailed analysis, visualizations, and further documentation, please refer to the Power BI report and associated files within the GitHub repository.
