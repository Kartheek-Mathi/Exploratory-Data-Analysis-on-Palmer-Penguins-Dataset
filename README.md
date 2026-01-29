# Exploratory Data Analysis on Palmer Penguins Dataset

## 📌 Overview
This repository contains an exploratory data analysis (EDA) and preprocessing study performed on the **Palmer Penguins dataset**.  
The project focuses on data cleaning, statistical analysis, visualization, outlier detection, normalization, and dimensionality reduction techniques to better understand penguin species characteristics.

The analysis is implemented using Python and standard data science libraries.

---

## 📂 Dataset
- **Dataset Name:** Palmer Penguins
- **Description:** Contains biological measurements of penguins from three species (*Adelie, Chinstrap, Gentoo*) collected from different islands.
- **Features Include:**
  - bill_length_mm
  - bill_depth_mm
  - flipper_length_mm
  - body_mass_g
  - species
  - island
  - sex

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## 📊 Analysis Tasks Performed

### Q1: Data Cleaning and Preprocessing
- Identified missing and incorrect values
- Handled missing data using appropriate strategies
- Ensured data consistency and validity

### Q2: Species-wise Statistical Analysis
- Computed the **average body mass** for Gentoo penguins

### Q3: Distribution Analysis
- Analyzed distributions of:
  - `bill_length_mm`
  - `bill_depth_mm`
- Computed **skewness** and **kurtosis** for each species
- Interpreted shape differences between distributions

### Q4: Outlier Detection
- Identified outliers using statistical methods (IQR / Z-score)
- Visualized outliers using boxplots and scatter plots

### Q5: Curse of Dimensionality & PCA
- Evaluated whether the dataset suffers from the curse of dimensionality
- Applied **Principal Component Analysis (PCA)**
- Explained variance and dimensionality reduction results

### Q6: Data Visualization
- Created **7 different visualizations** using:
  - `bill_length_mm`
  - `bill_depth_mm`
- Used scatter plots, regression plots, KDE plots, and more

### Q7: Grouped Feature Analysis
- Found maximum `flipper_length_mm` for each **species–island** combination
- Identified which species has the longest flippers on each island

### Q8: Feature Scaling
- Performed **Z-score normalization** on numerical features
- Prepared data for further machine learning tasks

---

## 📈 Visualizations
The repository includes multiple plots to visualize:
- Feature distributions
- Species comparisons
- Outliers
- PCA projections
- Relationship between bill measurements

---

## 📁 Repository Structure
```text
├── data/
│   └── penguins.csv
├── notebooks/
│   └── penguins_eda.ipynb
├── README.md
