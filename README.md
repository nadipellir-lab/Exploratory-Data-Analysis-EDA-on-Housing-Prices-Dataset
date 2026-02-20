# Exploratory Data Analysis (EDA) on Housing Prices Dataset

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a Housing Prices dataset using Python.  
The goal of the project is to understand the structure of the data, identify important features affecting house prices, detect missing values and outliers, and discover meaningful patterns using statistical analysis and data visualization.

EDA helps in preparing the dataset before applying Machine Learning models by improving data quality and feature understanding.

---

## 🎯 Objectives
- Understand dataset structure and feature distribution
- Identify missing values and handle them
- Detect and treat outliers
- Analyze relationships between features and house prices
- Perform correlation analysis
- Visualize patterns using plots and charts
- Prepare clean data for predictive modeling

---

## 🧰 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset Description
The dataset contains information about residential houses including:

- Lot Area
- Number of Bedrooms
- Number of Bathrooms
- Year Built
- Overall Quality
- Garage Area
- Living Area
- Sale Price (Target Variable)

The target variable of analysis is **SalePrice**.

---

## 🔍 Steps Performed in EDA

### 1. Data Loading
- Imported dataset using Pandas
- Checked dataset shape and column names

### 2. Data Inspection
- Used `.info()` and `.describe()` to understand data types and summary statistics
- Identified categorical and numerical features

### 3. Missing Value Analysis
- Detected missing values
- Handled missing data using mean, median, or mode imputation

### 4. Univariate Analysis
- Distribution plots (histograms)
- Boxplots
- Frequency counts

### 5. Bivariate Analysis
- Scatter plots (feature vs SalePrice)
- Bar plots for categorical variables

### 6. Correlation Analysis
- Generated correlation matrix
- Heatmap visualization to identify strongly related features

### 7. Outlier Detection
- Boxplots used to detect extreme values
- Outliers analyzed for impact on price

---

## 📈 Key Insights
- Overall Quality strongly affects house price
- Living Area has high positive correlation with SalePrice
- Houses with garages and recent construction years tend to have higher prices
- Some features contain missing values which required preprocessing
- Outliers exist in lot area and sale price

---

## 📂 Project Files
- `EDA_Housing_Prices.ipynb` → Jupyter Notebook containing full analysis
- `housing.csv` → Dataset used for analysis
- `plots/` → Generated visualization images

---

## ▶️ How to Run
1. Install Python (3.x)
2. Install required libraries:

3. Open Jupyter Notebook
4. Run `EDA_Housing_Prices.ipynb`

---

## 💡 Learning Outcomes
- Practical experience with data preprocessing
- Understanding feature relationships
- Handling missing values and outliers
- Data visualization techniques
- Preparing data for Machine Learning

---

## 🚀 Future Work
- Apply regression models to predict house prices
- Feature engineering
- Model evaluation and optimization

---

## 👨‍💻 Author
**Nadipelly Rajeshwar Rao**

---

## 📜 License
This project is for educational and learning purposes.
