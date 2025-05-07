# NextGen_internship_week2
## Internship Weekly Report - Week 2

**Name:** Sandeep Ravaji Patel
**Domain:** Data Science
**Week Number:** Week 2

### Task Description

**Objective:** To develop proficiency in data handling using Pandas and NumPy, focusing on operations like filtering, grouping, sorting, and analyzing datasets from real-world CSV files.

**Tasks Completed:**

* **Data Import and Exploration:**
    * Imported CSV files using Pandas (`read_csv`) and NumPy (`loadtxt`).
    * Explored dataset structure (e.g., Pokémon stats) and displayed top rows.
* **Data Filtering and Sorting:**
    * Filtered data based on conditions (e.g., Pokémon of type "Grass" or with high HP).
    * Sorted data by columns like "Attack," "Defense," and "Total" in ascending/descending order.
* **Descriptive Statistics:**
    * Used `describe()` to summarize numerical columns (mean, min, max, etc.).
    * Grouped data by categories (e.g., Pokémon types) to calculate averages.
* **Advanced Grouping and Aggregation:**
    * Grouped by "Type 1" and "Type 2" to analyze mean stats (e.g., highest average "Total" by type).
    * Counted Pokémon per type using `groupby` and custom aggregations.
* **Data Conversion and Cleaning:**
    * Converted string data to numerical types in NumPy arrays.
    * Handled missing values (e.g., `NaN` in "Type 2" column).

### Code Snippets / Design Screenshots

**Example 1: Sorting Pokémon by Attack and Defense**


**Example 2: Grouping by Type and Calculating Averages**


### Challenges Faced

* **Type casting of Ndarray:** Struggled with type casting of Ndarray as it contains alphabetic and numeric values in object format.
    * **Resolution:** Observed the first row carefully and type cast each column using the `astype(int)` method.
* **Complex Grouping Operations:** Confusion when aggregating multiple columns (e.g., mean vs. count).
    * **Resolution:** Referred to Pandas documentation for `groupby` syntax.
* **Performance Issues:** Slow operations on large datasets.
    * **Resolution:** Optimized by selecting specific columns (`df[['col1', 'col2']]`).

### Learning Outcome

* Pandas Proficiency: Mastered data filtering (`loc`), sorting, and grouping.
* Statistical Analysis: Used descriptive stats (`describe()`) and custom aggregations.
* Real-world Data Handling: Worked with CSV files and cleaned messy data.
* Debugging Skills: Improved error resolution (e.g., `TypeError` during conversions).

### Next Steps

For Week 3, the focus will be on:

* Data Visualization: Creating plots with Matplotlib/Seaborn.
* Advanced Pandas: Merging datasets, handling time-series data.
* Machine Learning Prep: Feature engineering and correlation analysis.

### Resources

* Pandas: [Pandas Documentation](https://pandas.pydata.org/docs/)
* NumPy: [NumPy Guide](https://numpy.org/doc/stable/)
* Dataset: [Kaggle Dataset](https://www.kaggle.com/datasets/abcsds/pokemon)
