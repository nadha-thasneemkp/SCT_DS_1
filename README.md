# SCT_DS_1
This project visualizes the relationship between **work hours per week** and **income categories** using the UCI Adult datasetsourced from Kaggle. After cleaning the data, histograms and KDE plots reveal patterns in how hours worked relate to income levels.

## 📌 Objective

To analyze whether individuals working more hours tend to earn more income. The income groups are divided into:
- `<=50K`
- `>50K`

## 🧹 Data Cleaning

- Replaced `?` with `NaN` to handle missing values
- Dropped rows with missing values using `dropna()`
- Displayed dataset size before and after cleaning

## 📊 Visualization

A histogram and KDE (Kernel Density Estimate) plot was created using Seaborn and Matplotlib:

- **X-axis**: Hours per week
- **Y-axis**: Density
- Separate color-coded distributions for `<=50K` and `>50K` income groups

### Key Findings:
- The majority of individuals earning **<=50K** work exactly **40 hours per week**, forming a sharp peak in the distribution.
- Those earning **>50K** tend to have a **wider range of working hours**, with many working more than 40 hours.
- Longer work hours appear to be associated with higher income, though not exclusively.
- However, not all individuals who work long hours earn more than $50K, suggesting that other factors also influence income.

  
These patterns suggest that while 40-hour weeks are common, **working longer hours may increase the likelihood of earning more** , though other factors also play a role.

## 📁 Files Included

- `adult.csv` – Cleaned dataset from Kaggle
- `Untitled5.ipynb` – Jupyter Notebook with cleaning and visualization code
- `README.md` – This documentation

## 📚 Dataset Source

[Adult Income Dataset on Kaggle](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)


**Acknowledgements**


This dataset named “adult” is found in the UCI machine learning repository
http://www.cs.toronto.edu/~delve/data/adult/desc.html

The detailed description on the dataset can be found in the original UCI documentation
http://www.cs.toronto.edu/~delve/data/adult/adultDetail.html



## 🛠️ Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

---

Feel free to explore or build upon this project!
