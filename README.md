# ITC-Stock-Performance-Dashboard
It loads, cleans, and analyzes ITC stock data, calculating key performance indicators. It then creates an interactive dashboard visualizing closing price trends, trading volume, daily price change distribution, and a correlation matrix, complete with a date range filter.

## Overview
This project focuses on loading, cleaning, and analyzing historical stock data for ITC. It calculates crucial financial indicators such as current price, 52-week high/low, and average trading volume. The core output is an interactive Dash application that allows users to explore stock performance through various visualizations.

## Data
The notebook expects a CSV file named `ITC-EQ-01-04-2000-to-31-03-2024.csv` to be uploaded. This file should contain historical stock data with columns such as 'date', 'open', 'high', 'low', 'close', and 'volume'. The data is preprocessed to handle missing values and convert the 'date' column to datetime objects.

## Dashboard Features
The interactive Dash dashboard offers the following functionalities:

*   **Key Performance Indicators (KPIs):** Displays current price, 52-week high, 52-week low, and average trading volume at a glance.
*   **Date Range Filter:** Users can select a specific date range to analyze stock data within that period.
*   **Download Filtered Data:** A button allows users to download the currently filtered dataset as a CSV file.
*   **Stock Closing Price Trend:** A line chart showing the closing price movement over time.
*   **Daily Trading Volume:** A bar chart illustrating the daily trading volume.
*   **Daily Price Change Distribution:** A pie chart breaking down the proportion of positive, negative, and no-change days.
*   **Correlation Matrix:** A heatmap displaying the correlation between various stock metrics (open, high, low, close, volume).

This dashboard provides a dynamic way to understand ITC's stock performance and identify potential patterns.

## Dashboard Preview 
<img width="1634" height="454" alt="image" src="https://github.com/user-attachments/assets/d0967810-960a-4cc9-95ea-b94f741163d7" />
<img width="609" height="450" alt="newplot" src="https://github.com/user-attachments/assets/eec2bd78-b24b-4d66-adb4-7659883b5932" />
<img width="609" height="450" alt="newplot (1)" src="https://github.com/user-attachments/assets/cd331ec5-43d9-446a-8277-4a447000bb6f" />
<img width="609" height="450" alt="newplot (2)" src="https://github.com/user-attachments/assets/5e4ef36b-b734-4717-93e3-ed6b9d6681b9" />
<img width="609" height="450" alt="newplot (3)" src="https://github.com/user-attachments/assets/29a92fd2-0c32-4e9a-8c89-6ed680ea2a42" />



