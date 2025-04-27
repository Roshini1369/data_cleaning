# data_cleaning
cleaning the given datasets
Key Features of a Scatter Matrix:
Pairwise Relationships: The scatter matrix plots all pairs of numerical columns, showing how each variable relates to every other variable in the dataset.

For each pair of variables, a scatter plot is displayed, showing the correlation between the two variables.

Diagonal: The diagonal axis typically shows the distribution of each individual variable, usually as histograms or density plots.

This helps identify the individual distribution (e.g., skewness, normality, spread) of each numerical variable.

Correlation Insights: The scatter plots help visualize potential correlations:

Positive Correlation: If the points form a straight line from the bottom-left to top-right, the variables have a positive correlation.

Negative Correlation: If the points form a line from the top-left to bottom-right, the variables are negatively correlated.

No Correlation: If the points are scattered with no discernible pattern, there’s likely no correlation.

Outliers: Any points that significantly deviate from the general trend or cluster in a scatter plot indicate outliers.

Clusters or Grouping: Grouped points in certain regions of the scatter plot might indicate clusters or groupings in the data, which could be significant for further analysis (e.g., customer segmentation).

When to Use a Scatter Matrix:
Exploratory Data Analysis (EDA): The scatter matrix is commonly used in the early stages of data analysis to get a sense of how variables interact with each other.

Correlation Identification: It helps in identifying the strength and direction of correlations between variables.

Outlier Detection: Outliers in the data can be easily spotted.

Pattern Recognition: It aids in spotting trends or patterns between variables, which may be crucial for modeling or further analysis.

Example Use Case:
For example, if you're working on a customer segmentation analysis project for an e-commerce company, a scatter matrix might help you understand how different customer behaviors (e.g., age, purchase amount, and frequency) relate to each other. It will allow you to see whether:

Older customers tend to purchase more.

Frequent buyers are associated with larger purchase amounts.

There are any outliers in customer purchase behavior.

Customization:
Hue: You can further customize the scatter matrix by adding a categorical column (e.g., customer segment or gender) to differentiate the points by color, allowing you to visually distinguish between different groups in the data.

Example of Scatter Matrix Insights:
Positive Correlation: If age and purchase amount have a positive correlation, older customers might tend to buy more expensive items.

Negative Correlation: If purchase frequency and time between purchases have a negative correlation, frequent buyers tend to have shorter intervals between their purchases.

Example of a Pairplot:
Here’s what a typical scatter matrix (pairplot) might look like:
