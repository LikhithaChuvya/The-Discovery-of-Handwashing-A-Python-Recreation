# The-Discovery-of-Handwashing-A-Python-Recreation


Dr. Ignaz Semmelweis’s discovery of the importance of handwashing in hospitals revolutionized healthcare and significantly reduced mortality rates. In this project, we will recreate Dr. Semmelweis’s discovery using Python. We will read the historical dataset, explore the relationship between variables over different periods, perform calculations to compare mortality rates before and after handwashing implementation, and visualize the impact of handwashing on reducing mortality rates.

In the provided code, we performed the following main tasks:

#1. **Data Loading and Preparation**:
   - We loaded the monthly and yearly datasets containing information about births, deaths, and clinic types.
   - For the monthly dataset, we converted the 'date' column to datetime format to facilitate time-based analysis.

#2. **Visualization of Monthly Mortality Rates**:
   - We visualized the monthly mortality rates by grouping the data by month and calculating the mean mortality rate for each month.
   - The resulting visualization is a line plot showing the trend of mortality rates across different months.

#3. **Visualization of Yearly Mortality Rates**:
   - We visualized the yearly mortality rates by plotting the mortality rates against years.
   - The resulting visualization is a line plot showing the trend of mortality rates over different years.

These visualizations help us understand the patterns and trends in mortality rates at both monthly and yearly levels, providing insights into how mortality rates vary over time. Additionally, by performing these visualizations, we can identify any potential anomalies or patterns that may require further investigation.

Trend Analysis:
We'll fit a linear regression model to the yearly mortality data to identify any significant trends over time.
For the trend analysis, we fit a linear regression model to the yearly mortality data and visualize the trend using a scatter plot of actual data points and a regression line.

Correlation Analysis:
We'll explore the correlation between mortality rates and birth rates to see if there's any relationship between these variables.
For the correlation analysis, we calculate the correlation coefficient between monthly mortality rates and birth rates and visualize the correlation using a heatmap.

Thank You!
