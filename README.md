# Stock-Price-Prediction

Role: Data Visualization Analysis

Description:
This is a script for data visualization and analysis of stock price data using the Pandas and Matplotlib libraries. The code reads stock price data from a CSV file, processes it, and creates a time series plot of high and low stock prices. Here is a summary of the key components and functionalities of the code:

Imports: The code imports the pandas library for data manipulation and the matplotlib library for data visualization.

Data Loading: The code loads historical stock price data from a CSV file named 'NFLX.csv' and sets the 'Date' column as the index for the DataFrame.

Data Plotting: The code utilizes Matplotlib to create a time series plot. It specifies the formatting of the x-axis to display dates in 'YYYY-MM-DD' format and set a day interval for tick marks.

Data Transformation: The code converts the date values in the DataFrame's index into datetime objects for plotting.

Plotting High and Low Prices: The code creates line plots for both the 'High' and 'Low' stock prices over time.

Labels and Legends: The code adds labels for the x and y-axes, and a legend to differentiate the 'High' and 'Low' price lines.

Customizing the Date Display: It formats and rotates the x-axis date labels for improved readability.

Displaying the Plot: The code displays the final plot.

This script is a demonstration of data visualization for stock price analysis, and it showcases the ability to load, process, and visualize time series data effectively. 
