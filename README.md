# Extracting and Visualizing Stock Data

This project aims to extract and visualize stock data and revenue for companies like Tesla (TSLA) and GameStop (GME) using popular Python libraries. This task involves extracting data from a dataset, a necessary part of data science, and visualizing it to support decision-making.

## Features

- Extracting stock data (for TSLA and GME) using **yfinance**.
- Web scraping Tesla and GameStop's revenue data from the web using **requests** and **BeautifulSoup**.
- Cleaning and processing the data (removing commas and dollar signs, dropping empty and null values).
- Defining a **Plotly** graphing function to create dual subplots for stock price and revenue.
- Plotting interactive graphs for both Tesla and GameStop using the extracted data.

## Requirements

The following libraries are required for the project to run successfully:

- `yfinance`
- `pandas`
- `requests`
- `beautifulsoup4`
- `plotly`
- `nbformat`

You can install these libraries in your Jupyter Notebook using the following commands:
```sh
!pip install yfinance==0.2.65
!pip install pandas==2.3.2
!pip install requests==2.32.3
!pip install beautifulsoup4==4.13.5
!pip install nbformat==5.10.4
!pip install plotly==5.24.1
