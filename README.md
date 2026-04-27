# 💡 Light Bulb Classification Model Using Multi-Criteria Analysis

## 📌 Overview

This project develops a rule-based classification model to detect inconsistencies in product categorization using multi-criteria analysis.

The model integrates statistical, textual, and technical variables to improve classification accuracy.

---

## 🎯 Key Results

- ✔ 17.13% of records were reclassified  
- ✔ Detection of inconsistencies in intermediate categories  
- ✔ Improved classification accuracy  

---

## ⚙️ Methodology

- Data cleaning and preprocessing  
- Price standardization (z-score normalization)  
- Brand normalization  
- Feature extraction (watts from text)  
- Outlier detection (IQR method)  
- Rule-based classification model  

---

## 📊 Key Visualizations

### Price Distribution
![Price Distribution](images/price_distribution.png)

### Outlier Detection
![Outliers](images/outliers_boxplot.png)

### Classification Transition
![Transition](images/transition_matrix.png)

### Model Results
![Model Results](images/model_results.png)

### Watts Distribution
![Watts](images/watts_distribution.png)

---

## 💡 Business Value

This model can be applied to:

- Data quality validation  
- Product classification systems  
- Market research and pricing analysis  
- Survey data auditing  
- Decision support systems  

---

## 🔐 Data Disclaimer

The dataset used in this project has been anonymized. Sensitive variables were removed, and numerical values were transformed and standardized to preserve confidentiality while maintaining analytical integrity.

---

## 🛠 Tools & Technologies

- R (tidyverse, dplyr, ggplot2, stringr)
- RMarkdown
- Data cleaning & preprocessing
- Statistical analysis
- Rule-based modeling 

---

## 📂 Project Structure

├── bombillo.Rmd
├── bombillo.html
├── images/
│ ├── price_distribution.png
│ ├── outliers_boxplot.png
│ ├── transition_matrix.png
│ ├── model_results.png
│ └── watts_distribution.png
└── .gitignore

---

## 👨‍💻 Author

**Gari Jerez**  
Data Analyst | Economic & Statistical Modeling
