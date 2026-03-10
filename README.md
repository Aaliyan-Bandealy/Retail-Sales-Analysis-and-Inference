# Sales Data Cleaning and Business Analysis

## Project Overview

This project analyses transactional sales data using Python, focusing on data cleaning, exploratory analysis, statistical testing, and business insight generation.

The objective of the project is to transform raw transactional data into an analysis-ready dataset and extract meaningful insights that help understand revenue drivers, product performance, and customer behaviour.

The workflow includes data integration, cleaning, outlier treatment, exploratory analysis, hypothesis testing, and inference modelling.

---

## Key Objectives

- Clean and integrate multiple large sales datasets
- Handle missing values, inconsistent labels, and formatting errors
- Detect and treat outliers in sales-related variables
- Explore business trends using visual analysis
- Perform hypothesis testing for key business questions
- Use regression-based inference to identify drivers of revenue

---

## Dataset

The project uses three files:

- `Dataset1.csv`
- `Dataset2.csv`
- `Metadata.xlsx`

Because the datasets are large, they are **not included in this repository**.

You can download them from the following Google Drive folder:

Dataset Download Link  
https://drive.google.com/drive/folders/1_R0VKoi_f0O56H5wmu5MHiFU7pyZ5ELL?usp=sharing

After downloading the files, place them inside the `data/` folder.

## Tools and Libraries

The analysis was conducted using the following tools:

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- SciPy
- Statsmodels
- OpenPyXL

---

## Analysis Performed

### 1. Data Cleaning

The raw datasets were cleaned and prepared through several steps:

- Combined multiple datasets into a unified analysis table
- Removed columns with excessive missing values
- Standardised text fields by trimming spaces and correcting inconsistent labels
- Converted accounting dates into proper datetime format
- Removed invalid records and incomplete observations
- Treated extreme outliers in sales, cost, and quantity variables
- Examined distribution skewness and applied transformations where necessary

---

### 2. Exploratory Data Analysis

Several visual analyses were performed to understand the structure of the data:

- Monthly sales trends over time
- Customer retention curve
- Top business chains by total sales
- Average profit margin by currency
- Sales distribution by light source category

---

### 3. Statistical Hypothesis Testing

The project investigates multiple business questions using statistical tests:

- Whether LED and Traditional light sources differ in average profit margin
- Whether A-class and C-class products differ in average sales value
- Whether invoices in USD and AUD differ in profit margin

---

### 4. Inference Modelling

Regression-based inference was used to evaluate how different factors influence sales performance, including:

- Effect of warehouse location on sales
- Impact of order type categories on revenue
- Influence of product group classification on sales value

---

## How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/aaliyan-bandealy/Sales-Data-Cleaning-and-Business-Analysis.git
```

### 2. Navigate to the project folder

```
cd Sales-Data-Cleaning-and-Business-Analysis
```

### 3. Install required dependencies

```
pip install -r requirements.txt
```

### 4. Download the datasets

Download the datasets from:

https://drive.google.com/drive/folders/1_R0VKoi_f0O56H5wmu5MHiFU7pyZ5ELL?usp=sharing

Place the downloaded files into the `data/` folder.

### 5. Open the notebook

```
notebook/sales_data_analysis.ipynb
```

Run the notebook cells sequentially to reproduce the analysis.

---

## Skills Demonstrated

This project demonstrates several core analytics skills:

- Data cleaning and preprocessing
- Handling messy real-world datasets
- Exploratory data analysis
- Business insight generation
- Cohort and retention analysis
- Statistical hypothesis testing
- Regression and inference modelling
- Data storytelling using Python
