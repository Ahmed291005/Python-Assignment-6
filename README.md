# 📊 Business Data Analysis — Customer, Product & Engagement Analytics

A comprehensive **Business Data Analysis** project containing complete **Exploratory Data Analysis (EDA)**, **Data Cleaning**, and **Business Insight Generation** of six real-world datasets using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

This project was completed as part of a university Data Analysis assignment. All six datasets were analyzed in a **single Jupyter Notebook**, with 30 structured business questions answered through code, visualizations, and insights.

---

## 📁 Datasets Analyzed

### 1️⃣ Customers Dataset (`customers.xlsx`)
Contains demographic information of 100 customers including age, gender, and geography reference.

**Major Analysis**
- Total unique customer count
- Age category distribution (Young, Adult, Senior)
- Gender distribution
- Average purchase value by gender
- Engagement score by age group
- Gender vs rating comparison

---

### 2️⃣ Geography Dataset (`geography.xlsx`)
Contains regional and city-level information for 10 European locations linked to customers.

**Major Analysis**
- Customer distribution by country/region
- Average review rating by country
- Average engagement score by country

---

### 3️⃣ Products Dataset (`products.xlsx`)
Contains 20 sports products with pricing and category information.

**Major Analysis**
- Product price distribution
- Most purchased products (Top 10)
- Highest and lowest rated products
- Category-level rating comparison
- Views-to-purchase ratio by category

---

### 4️⃣ Customer Reviews Dataset (`customer_reviews.xlsx`)
Contains 1,363 product reviews with star ratings (1–5) and review text.

**Major Analysis**
- Overall rating distribution
- Average rating by product
- Average rating by gender
- Average rating by country/region
- Category-level rating analysis

---

### 5️⃣ Engagement Data Dataset (`engagement_data.xlsx`)
Contains 4,621 content engagement records including Views, Clicks, Likes, Content Type, and Campaign ID.

**Major Analysis**
- Total Views, Clicks, and Likes
- Overall Engagement Rate & CTR
- Engagement rate per product
- Most viewed and most clicked products
- Least engaged products
- Monthly conversion trend
- Campaign CTR analysis
- Top and lowest performing campaigns

---

### 6️⃣ Customer Journey Dataset (`customer_journey.xlsx`)
Contains 4,011 funnel stage records tracking customer movement from Homepage → ProductPage → Checkout → Purchase.

**Major Analysis**
- Conversion funnel analysis
- Drop-off analysis by stage
- Average duration by stage
- Monthly journey trend
- Purchase behavior by demographics

---

## 📌 Project Workflow

Each dataset follows a complete analysis pipeline:

- Dataset Loading
- Initial Data Inspection (shape, info, head)
- Missing Value Analysis
- Duplicate Record Check
- Data Type Validation & Conversion
- Data Cleaning & Preprocessing
- Dataset Merging (customers + geography + products + reviews + engagement + journey)
- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Data Visualization
- Business Insight Generation

---

## ❓ Assignment Questions Covered (30 Questions)

### Customer Analysis (Q1–Q10)
1. Total unique customers
2. Age category distribution (Young, Adult, Senior)
3. Gender distribution
4. Average rating by age category
5. Average purchase value by gender
6. Country with most customers
7. Average review rating by country
8. Average engagement score by country
9. Age group with highest engagement
10. Male vs Female rating comparison with graph

### Product Analysis (Q11–Q20)
11. Top 10 most purchased products
12. Most reviewed product
13. Top 10 most engaged products
14. Average rating by product category
15. Average engagement by category
16. Average views vs clicks by category
17. Bottom 10 lowest rated products
18. Top 10 highest rated products
19. Category with high views but low purchases
20. Product popularity bar chart

### Engagement Analysis (Q21–Q28)
21. Total Views, Clicks, and Likes
22. Overall Engagement Rate
23. Engagement Rate per product
24. Most viewed and most clicked products
25. Least engaged products
26. Monthly conversion trend
27. CTR per Campaign ID
28. Top and lowest performing campaigns

### Combined Analysis (Q29–Q30)
29. Engagement vs Rating relationship (Scatter Plot + Correlation)
30. Correlation Matrix Heatmap (Views, Clicks, Likes, Rating, Duration, Purchases) with Business Insights

---

## 📈 Visualizations Used

The notebook includes a wide range of visualization techniques:

- **Histograms** — Age and price distributions
- **Bar Charts** — Customer counts, product ratings, campaign CTR
- **Horizontal Bar Charts** — Top/bottom product rankings
- **Pie Charts** — Gender distribution, rating share
- **Box Plots** — Rating distribution by gender
- **Line Charts** — Monthly engagement and conversion trends
- **Scatter Plots** — Engagement vs Rating relationship with trend line
- **Grouped Bar Charts** — Views vs Clicks by category, Top 10 engagement breakdown
- **Correlation Heatmaps** — Variable relationships across all numeric features

Each visualization is accompanied by a printed business insight explaining observations and recommended actions.

---

## 🛠 Technologies Used

- Python 3.10
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL (for reading .xlsx files)

---

## 🎯 Learning Outcomes

This project demonstrates practical experience in:

- Data Loading from multiple Excel files
- Data Cleaning and Preprocessing
- Handling Missing Values
- Duplicate Detection and Removal
- Multi-dataset Merging (6 datasets joined)
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Customer Segmentation Analysis
- Product Performance Analysis
- Engagement & Campaign Analytics
- Funnel / Conversion Analysis
- Correlation Analysis
- Data Visualization
- Business Insight Generation
- Working with Real-World Business Datasets

---

## 📂 Project Structure

```
Business_Data_Analysis/
│
├── businesss_anylysis_project.ipynb   ← Main Jupyter Notebook (all 30 questions)
│
├── customers.xlsx                     ← Customer demographics
├── geography.xlsx                     ← Region and city data
├── products.xlsx                      ← Product catalog with prices
├── customer_reviews.xlsx              ← Product reviews and ratings
├── engagement_data.xlsx               ← Views, Clicks, Likes, Campaign data
├── customer_journey.xlsx              ← Funnel stage and action records
│
└── README.md                          ← This file
```

---

## ▶️ How to Run

1. Download all files and place them in the **same folder**
2. Open `businesss_anylysis_project.ipynb` in Jupyter Notebook or JupyterLab
3. Install required libraries if not already installed:
   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```
4. Run all cells sequentially (Cell → Run All)

---

## 📚 Assignment Information

**Course:** AI & Data Analysis
**Assignment Title:** Business Data Analysis — Customer, Product & Engagement Analytics
**Datasets Covered:**
- Customers Dataset
- Geography Dataset
- Products Dataset
- Customer Reviews Dataset
- Engagement Data Dataset
- Customer Journey Dataset

**Development Environment:** Jupyter Notebook
