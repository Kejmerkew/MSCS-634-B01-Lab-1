# Lab 1 – Data Visualization, Preprocessing, and Statistical Analysis

## Purpose of the Lab

The purpose of this lab was to apply key data analysis techniques using Python and Jupyter Notebook. The assignment focused on data visualization, data preprocessing, statistical analysis, scaling, and correlation analysis. Using the Seattle weather dataset, I explored the structure of the data, cleaned and transformed it, and performed statistical calculations to better understand its characteristics. This lab helped reinforce foundational concepts in data mining and data preparation.

---

## Dataset Used

The dataset used for this lab was the Seattle weather dataset, which includes variables such as:

- Date
- Precipitation
- Maximum Temperature
- Minimum Temperature
- Wind Speed
- Weather Type

---

## Key Insights

### Data Visualization
- The line plot showed trends in maximum temperature over time, helping identify seasonal patterns.
- The scatter plot helped explore relationships between variables such as wind speed and temperature.
- The histogram displayed the distribution of temperature values.
- The box plot helped identify potential outliers in the dataset.

### Statistical Analysis
- Central tendency measures (mean, median, mode) summarized the typical temperature values.
- Dispersion measures (range, variance, standard deviation, and IQR) showed how spread out the temperature data is.
- The correlation matrix helped identify relationships between numerical variables, which is useful for predictive modeling.

### Data Preprocessing
- Missing values were checked and confirmed to be handled.
- Outlier detection was performed using the IQR method.
- Data reduction techniques such as sampling and column removal were applied.
- Min-Max scaling and discretization were used to normalize and categorize the data.

---

## Challenges and Decisions

One challenge during this lab was ensuring that the correct preprocessing techniques were applied appropriately to the dataset. Another challenge involved understanding how to detect and handle outliers using the IQR method. Additionally, selecting meaningful visualizations required careful consideration of which variables would provide useful insights.

I decided to focus on the `temp_max` column for most statistical and preprocessing tasks because it provides meaningful information about weather patterns and works well for analysis and visualization.

---

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib

---

## Conclusion

This lab provided hands-on experience with data exploration, cleaning, visualization, and statistical analysis. These techniques are essential for preparing real-world datasets for deeper analysis and machine learning applications.
