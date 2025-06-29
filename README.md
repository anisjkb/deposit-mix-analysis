# Gender-Based Account Mix Analysis in Retail Banking

This repository contains the code and data for an analysis of a retail bank's customer account portfolio, segmented by product type and gender. The project uses Python and common data science libraries to uncover insights from the customer data and provide actionable recommendations.

---

### Table of Contents
1.  [Project Overview](#project-overview)
2.  [Key Questions Addressed](#key-questions-addressed)
3.  [Visualizations](#visualizations)
4.  [Key Insights](#key-insights)
5.  [Business Recommendations](#business-recommendations)
6.  [Technologies Used](#technologies-used)
7.  [How to Run](#how-to-run)
8.  [Data Source](#data-source)

---

### Project Overview
The goal of this project is to analyze the distribution of customer accounts across different product types (e.g., Low Cost, No Cost) and genders. By understanding these distributions, a financial institution can identify opportunities for targeted marketing, product development, and strategies to promote financial inclusion.

### Key Questions Addressed
* What is the overall distribution of bank accounts by gender?
* How does account ownership vary across different product categories like "Low Cost" and "No Cost" accounts?
* Which specific products show a significant gender gap, and where are the opportunities for growth?
* What strategic actions can the bank take to better serve underrepresented segments?

### Visualizations
This analysis produced several key visualizations to illustrate the findings. The images are located in the `/images` directory.

1.  **Total Accounts by Gender (Donut Chart):** A high-level view of the gender distribution across all accounts.
    ![Total Accounts by Gender](images/total_ac_gender_donut.png)

2.  **Total Accounts by Deposit Type (Bar Chart):** Shows the popularity of different product categories.
    ![Total Accounts by Deposit Type](images/total_ac_deposit_type.png)

3.  **Account Engagement by Gender (Grouped Bar Chart):** A comparative view of how genders are represented within each product type.
    ![Account Engagement by Gender](images/deposit_engagement_by_gender.png)

4.  **Percentage of Accounts by Gender (Bar Chart):** A normalized view showing the percentage split of genders within each deposit type.
    ![Gender Percentage by Deposit](images/gender_percentage_by_deposit.png)


### Key Insights
* **Female Dominance in Low-Cost Accounts:** The female segment holds a significantly higher number of accounts, primarily driven by "Low Cost" products like Savings Accounts and social program accounts (VGD, SSN).
* **Male Concentration in No-Cost Accounts:** The male segment shows stronger representation in "No-Cost" products, particularly standard Current Accounts.
* **Clear Segmentation:** There is a distinct difference in product preference between genders, indicating an opportunity for more precise customer segmentation and targeted strategies.

### Business Recommendations
* **Targeted Campaigns:** Develop marketing initiatives to promote "Low Cost" savings products to the male segment.
* **Enhance Product Offerings:** Investigate the features of "No Cost" accounts to make them more attractive to the female segment.
* **Leverage Existing Strengths:** Retain and grow the female customer base in "Low Cost" accounts by introducing loyalty programs or tiered benefits.

### Technologies Used
* Python 3.x
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

### How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/deposit-mix-analysis.git](https://github.com/your-username/deposit-mix-analysis.git)
    cd deposit-mix-analysis
    ```
2.  **Install dependencies:**
    It is recommended to use a virtual environment.
    ```bash
    pip install pandas matplotlib seaborn jupyterlab
    ```
3.  **Launch Jupyter:**
    ```bash
    jupyter lab
    ```
4.  Open the `cust-ac-details.ipynb` notebook and run the cells to reproduce the analysis and visualizations.

### Data Source
* `product_wise_ac_info.csv`: This file contains the aggregated data on the number of accounts for each product description, segmented by product nature, product type, and gender.
