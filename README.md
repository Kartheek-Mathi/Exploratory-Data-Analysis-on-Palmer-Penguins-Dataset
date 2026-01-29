# Exploratory Data Analysis on Palmer Penguins Dataset

## 📌 Overview
This repository presents an exploratory data analysis (EDA) and preprocessing study conducted on a **subset of the Palmer Penguins dataset**.  
The project focuses on cleaning raw data, performing statistical analysis, visualizing feature relationships, detecting outliers, applying normalization, and reducing dimensionality using PCA.

A recorded execution video is included to demonstrate the complete workflow and outputs.

---

## 📂 Dataset
- **File:** `penguins.csv`
- **Source:** Palmer Penguins Dataset (subset)
- **Description:**  
  The dataset contains morphological measurements of penguins collected from Palmer Station, Antarctica. It includes species, island location, and physical characteristics such as bill dimensions, flipper length, and body mass.
- **Species Included:** Adelie (subset used for analysis)
- **Missing Values:** Present and handled during preprocessing.

### Features
- `species`
- `island`
- `bill_length_mm`
- `bill_depth_mm`
- `flipper_length_mm`
- `body_mass_g`
- `sex`

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook

---

## 📊 Analysis Performed

- Identified missing, null, and inconsistent values in the dataset and applied appropriate preprocessing techniques to clean the data.
- Computed descriptive statistics, including the average body mass for Gentoo penguins.
- Analyzed the distributions of bill length and bill depth across different penguin species by calculating skewness and kurtosis.
- Detected outliers in numerical features using statistical methods such as the Interquartile Range (IQR) and Z-score.
- Visualized outliers using boxplots and scatter plots for better interpretability.
- Evaluated the dimensionality of the dataset and applied Principal Component Analysis (PCA) to reduce dimensions while preserving variance.
- Generated multiple visualizations to explore the relationship between bill length and bill depth.
- Grouped data by species and island to identify the maximum flipper length for each combination and compared species dominance per island.
- Applied Z-score normalization to numerical features to standardize the dataset for further analysis.

---

## 📈 Visualizations
The notebook includes:
- Distribution and density plots
- Feature comparison plots across species
- Outlier visualizations
- PCA projection plots
- Relationship plots between morphological features

---

## 🎥 Execution Demo
- **File:** `video.mp4`
- **Description:**  
  A recorded walkthrough demonstrating the execution of the Jupyter Notebook, including data loading, preprocessing, visualization, and analysis outputs.

---

## 📁 Repository Structure
```text
├── README.md
├── penguins.csv
├── penguins_eda.ipynb
└── video.mp4
