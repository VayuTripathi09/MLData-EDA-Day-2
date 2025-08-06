# 📊 Day 2: Exploratory Data Analysis (EDA)

## ✅ Objective
Perform exploratory data analysis to understand the structure, distribution, relationships, and patterns in the flight pricing dataset using statistical summaries and visualizations.

---

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly (for interactive visualizations)

---

## 🧾 Dataset Columns
- `airline`
- `flight`
- `source_city`
- `departure_time`
- `stops`
- `arrival_time`
- `destination_city`
- `class`
- `duration`
- `days_left`
- `price`

---

## 📌 Key EDA Steps

### 1. **Basic Dataset Inspection**
- Loaded dataset using `pandas.read_csv()`
- Viewed data shape, column types, and null values
- Used `describe()` for summary statistics

### 2. **Univariate Analysis**
- Count plots for categorical columns (e.g., airline, class)
- Distribution plots for numerical columns (e.g., price, days_left)

### 3. **Bivariate Analysis**
- Boxplots: `price` vs `airline`, `class`, and `stops`
- Scatter plot: `price` vs `days_left` with hue as `class`

### 4. **Multivariate Analysis**
- Correlation heatmap for numeric features
- Visualized potential outliers in `price`

### 5. **Interactive Visualizations (Plotly)**
- Interactive scatter plot: `price` vs `days_left` by `airline`
- Interactive box plot for `price` by `class`

---

## 📈 Insights Discovered
- Price trends vary significantly across airlines and classes.
- First class flights are consistently more expensive.
- Fewer days left typically results in higher prices.
- Flights with more stops often cost less but vary widely.

---

## 📂 Output
- Cleaned and analyzed dataset (`df`)
- Multiple plots for visual understanding
- Interactive Plotly graphs (if running in Jupyter/Colab)

---

## ✅ Status
✔️ EDA completed successfully and ready for feature engineering.

---

## 📅 Day 2 Completed
