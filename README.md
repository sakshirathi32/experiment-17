AIM: Basic Charts and Visual Encoding
THEORY

This experiment is based on Data Visualization, which is an important part of data analysis used to convert complex datasets into visual forms such as charts and graphs. These visual representations help in identifying patterns, trends, relationships, and outliers more easily. By using Python libraries like Matplotlib and Seaborn, different types of plots such as bar charts, histograms, scatter plots, and line charts can be created to understand both categorical and numerical data effectively.

Visualizations transform mathematical and statistical data into simple graphical forms that are easier for humans to understand and analyze.

Line Chart

A line chart is used to observe trends over time. It places independent variables such as days or months on the X-axis and dependent variables such as sales or temperature on the Y-axis. The points are connected using continuous lines to show changes over time.

Bar Chart

A bar chart is used to compare different categories of data. It represents values using rectangular bars, where the height of each bar is proportional to the value it represents.

Histogram

A histogram is used to show the distribution of continuous numerical data. The data is divided into equal intervals called bins, and the number of values in each bin is represented using adjacent vertical bars.

Scatter Plot

A scatter plot is used to identify relationships or correlations between two variables. Individual data points are plotted as dots on a graph. If the points form a visible pattern, it indicates a relationship between the variables.

ONE-LINE EXPLANATIONS OF FUNCTIONS USED
import matplotlib.pyplot as plt – Imports the main library used for creating graphs and charts in Python
import seaborn as sns – Imports Seaborn, which provides advanced and attractive statistical visualizations
plt.bar() – Creates a bar chart using rectangular bars for category comparison
plt.xlabel() / plt.ylabel() – Adds labels to the x-axis and y-axis
plt.title() – Adds a heading to describe the chart
plt.show() – Displays the final graph on the screen
plt.hist() – Creates a histogram to show data distribution using bins
plt.scatter() – Generates a scatter plot to show the relationship between two variables
plt.pie() – Creates a pie chart to show proportions as parts of a circle
plt.legend() – Displays labels for different elements in the graph
sns.lineplot() – Draws a line chart to show trends over time
sns.countplot() – Creates bars to show the frequency of categorical data
sns.boxplot() – Displays data distribution using minimum, quartiles, median, and maximum values
CONCLUSION

In this experiment, it was understood that Data Visualization plays a major role in presenting data clearly and effectively. By using suitable charts such as bar charts for comparison, histograms for data distribution, and scatter plots for correlation analysis, complex data can be simplified and understood easily. This helps in better analysis, interpretation, and decision-making.
