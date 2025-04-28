# 🚢 Titanic Dataset Analysis

A complete data cleaning, visualization, and insights extraction project using the Titanic dataset, powered by **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

## 📊 Project Workflow

### 1. Import Libraries
- pandas
- numpy
- matplotlib
- seaborn

### 2. Load Dataset
- Loaded Titanic dataset from Seaborn’s sample datasets.

### 3. Data Cleaning
- Handled missing values:
  - Filled missing **age** values with **median**.
  - Filled missing **embarked** values with **mode**.
  - Added `'Unknown'` category for missing **deck** values.
- Removed duplicate rows.

### 4. Outlier Detection
- Visualized **age** and **fare** outliers using **boxplots**.

### 5. Exploratory Data Analysis (EDA)
- Bar plots for categorical features: `sex`, `class`, `embarked`, `who`, `deck`, `alive`.
- Histograms for numerical features: `age`, `fare`, `sibsp`, `parch`.
- Correlation heatmap for numeric columns.

### 6. Key Insights
- Majority of passengers were **male** and traveled in **3rd class**.
- **Females** and **1st class** passengers had higher survival rates.
- **Fare** shows some extreme outliers (very expensive tickets).
- **Age** distribution is right-skewed; most passengers were young adults.
- **Deck** information was mostly missing, now labeled as `'Unknown'`.

### 📈 Visualizations Included

Boxplots for outlier detection

Countplots for categorical variables

Histograms with KDE plots for numerical variables

Correlation heatmap

