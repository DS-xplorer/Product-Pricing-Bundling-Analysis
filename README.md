# Product Pricing & Bundling Analysis

## 📌 Project Overview

This project focuses on analyzing retail transaction data to identify **pricing opportunities, product price elasticity, and product bundling opportunities** using Python.

The analysis follows an end-to-end data analytics workflow, from data quality assessment and cleaning to exploratory analysis, strategic pricing analysis, product bundling, and final business recommendations.

The objective is to transform retail transaction data into **actionable insights that can support pricing decisions, cross-selling strategies, and revenue growth**.

---

## 🎯 Business Objectives

* Assess the quality and reliability of retail transaction data.
* Clean and prepare the data for analysis.
* Analyze sales, revenue, quantity, and pricing patterns.
* Evaluate product-level price elasticity.
* Identify potential pricing opportunities.
* Discover products frequently purchased together.
* Identify high-potential product bundles.
* Convert analytical findings into actionable business recommendations.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Jupyter Notebook**
* Exploratory Data Analysis
* Price Elasticity Analysis
* Product Bundling Analysis
* CSV/Excel Data Processing

---

## 📊 Dataset

The dataset used in this project is the **Online Retail II** dataset, obtained from Kaggle.

The dataset contains retail transactions from a UK-based online retailer and includes information such as invoice number, product code, product description, quantity, invoice date, unit price, customer ID, and country.

### Dataset Source

**Kaggle — Online Retail Dataset**

[View Dataset on Kaggle](https://www.kaggle.com/lakshmi25npathi/online-retail-dataset?utm_source=chatgpt.com)

The original dataset is **not included in this repository because of its large file size**. The analysis was performed using the full dataset, while sample output files are provided in the repository for reference.

---

## 📂 Project Structure

```text
Product-Pricing-Bundling-Analysis/
│
├── notebooks/
│   ├── 01_data_quality_assessment.ipynb
│   ├── 02_Advanced_Data_Cleaning_and_Feature_Engineering.ipynb
│   ├── 03_Advanced_EDA_&_Pricing_Analysis.ipynb
│   ├── 04_Strategic_Pricing_Analysis.ipynb
│   ├── 05_Product_Bundling_Analysis.ipynb
│   └── 06_Final_Business_Insights.ipynb
│
├── insights_&_recommendations/
│   ├── business_recommendations.csv
│   ├── final_bundle_recommendations.csv
│   ├── final_pricing_opportunities.csv
│   └── key_business_insights.csv
│
└── outputs/
    ├── basket_analysis_clean_sample.csv
    ├── customer_analysis_clean_sample.csv
    ├── data_quality_report_sample.csv
    ├── data_quality_summary_sample.csv
    ├── pricing_sales_clean_sample.csv
    └── product_elasticity_sample.csv
```

---

# 📓 Analysis Workflow

## 1. Data Quality Assessment

The first notebook evaluates the raw dataset for:

* Missing values
* Duplicate records
* Negative and zero quantities
* Missing customer information
* Pricing issues
* Transaction-level data quality
* Dataset structure and statistics

This step helps establish the quality and reliability of the data before further analysis.

---

## 2. Advanced Data Cleaning & Feature Engineering

The second notebook prepares the data for analysis by:

* Standardizing column names and text fields
* Handling duplicate records
* Identifying returns
* Filtering invalid sales transactions
* Creating revenue-related features
* Creating date and time features
* Creating price bands
* Preparing customer, sales, and basket-level datasets

---

## 3. Advanced EDA & Pricing Analysis

The third notebook analyzes:

* Sales and revenue performance
* Product-level performance
* Price bands
* Quantity and revenue patterns
* Monthly pricing trends
* Monthly quantity trends
* Price-quantity relationships
* Product-level price elasticity

---

## 4. Strategic Pricing Analysis

The fourth notebook translates pricing analysis into strategic actions by:

* Classifying products based on price elasticity
* Identifying elastic and inelastic products
* Evaluating product revenue contribution
* Identifying high-priority pricing opportunities
* Developing pricing strategies based on product behavior

---

## 5. Product Bundling Analysis

The fifth notebook identifies products with strong purchase associations and potential cross-selling opportunities.

The analysis evaluates:

* **Support**
* **Confidence**
* **Lift**
* **Bundle Score**
* Revenue contribution

These metrics are used to identify products that could potentially be offered together as bundles or recommended for cross-selling.

---

## 6. Final Business Insights

The final notebook consolidates the analysis into:

* Key business insights
* Pricing opportunities
* Product bundle opportunities
* Business actions
* Strategic recommendations

---

# 📈 Key Analytical Concepts

## Price Elasticity

Price elasticity analysis is used to understand how changes in product price are associated with changes in demand.

Products are classified into categories such as:

* **Elastic**
* **Inelastic**
* **Positive/Unusual**

These classifications help identify products where pricing changes may have different effects on demand.

---

## Product Bundling

Product combinations are evaluated using association metrics.

### Support

Measures how frequently a product combination occurs in transactions.

### Confidence

Measures how often one product is purchased when another product is purchased.

### Lift

Measures the strength of association between two products compared with what would be expected if they were independent.

Higher lift values indicate stronger product associations and potential cross-selling opportunities.

---

# 💡 Business Recommendations

The analysis provides recommendations such as:

* Protecting prices for highly price-sensitive products.
* Testing moderate price increases for relatively inelastic products.
* Prioritizing high-revenue products when developing pricing strategies.
* Using strong product associations for cross-selling.
* Creating bundles based on observed customer purchase behavior.
* Prioritizing bundle opportunities using both association strength and revenue potential.

Detailed results are available in:

```text
insights_&_recommendations/
```

---

# 📁 Output Files

The `outputs/` folder contains **sample versions of the processed datasets** to keep the GitHub repository lightweight.

These include:

* `basket_analysis_clean_sample.csv`
* `customer_analysis_clean_sample.csv`
* `data_quality_report_sample.csv`
* `data_quality_summary_sample.csv`
* `pricing_sales_clean_sample.csv`
* `product_elasticity_sample.csv`

The `insights_&_recommendations/` folder contains the final analytical outputs:

* `key_business_insights.csv`
* `business_recommendations.csv`
* `final_pricing_opportunities.csv`
* `final_bundle_recommendations.csv`

---

# 📦 Dataset Availability

The original `online_retail_II.xlsx` dataset is **not included in this GitHub repository due to its large file size**.

The complete analysis was performed using the full dataset obtained from Kaggle. Sample processed files are included to demonstrate the structure of the data and analytical outputs.

**Dataset Source:**
[Kaggle — Online Retail Dataset](https://www.kaggle.com/lakshmi25npathi/online-retail-dataset?utm_source=chatgpt.com)

---

# 🚀 Project Outcome

This project demonstrates an end-to-end **Python-based Data Analytics workflow**, covering:

**Data Quality → Data Cleaning → Feature Engineering → EDA → Pricing Analysis → Price Elasticity → Strategic Pricing → Product Bundling → Business Recommendations**

The project combines technical data analysis with business-oriented thinking to identify opportunities for **better pricing decisions, cross-selling, and revenue growth**.
