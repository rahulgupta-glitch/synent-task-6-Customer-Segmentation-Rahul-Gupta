# Customer Segmentation Analysis

## 🎯 Objective
* **Goal:** To categorize customers into distinct groups (clusters) based on their purchasing behavior and demographic data.
* **Business Value:** Enables the marketing team to build targeted strategies, optimize ad campaigns, and improve customer retention by understanding specific buyer personas.

## 🛠️ Tools & Technologies Used
* **Environment:** Visual Studio Code / Jupyter Notebook
* **Programming Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn` (for distribution plots and cluster visualizations)
* **Machine Learning:** `scikit-learn` (K-Means Clustering, Data Scaling)

## 🔄 Steps Performed
* **Exploratory Data Analysis (EDA):** Analyzed the distributions and relationships of variables like Age, Annual Income, and Spending Score.
* **Data Preprocessing:** Selected relevant features (typically Annual Income and Spending Score) and applied feature scaling to ensure the clustering algorithm performs accurately.
* **Finding the Optimal Clusters:** Utilized the **Elbow Method** (calculating Within-Cluster Sum of Squares) to mathematically determine the ideal number of customer segments (usually 5).
* **Model Training:** Applied the **K-Means Clustering** algorithm to group the data points into the predetermined number of clusters.
* **Cluster Visualization:** Created 2D scatter plots to visually map the customer segments and assigned descriptive labels to each group based on their characteristics.

## 💡 Key Insights & Outcomes
* **5 Distinct Buyer Personas:** Successfully identified five clear customer segments:
    1. **Target Customers:** High Income, High Spending Score (Prime targets for premium products).
    2. **Careful Spenders:** High Income, Low Spending Score (Needs convincing/high-value propositions).
    3. **Standard Customers:** Average Income, Average Spending Score (The baseline volume drivers).
    4. **Impulsive Spenders:** Low Income, High Spending Score (Good targets for sales and limited-time offers).
    5. **Frugal Customers:** Low Income, Low Spending Score (Requires heavy discounts to convert).
* **Strategic Value:** The business can now stop using a "one-size-fits-all" marketing approach and instead deploy personalized campaigns that maximize ROI for each specific customer tier.
