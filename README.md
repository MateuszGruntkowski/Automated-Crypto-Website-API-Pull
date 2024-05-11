## 1. Downloading data from API:
The code starts by importing the necessary Python libraries such as requests and json. The API query parameters are then defined, including the URL, request parameters, and headers. The session is created including the headers, and then a GET request is sent to retrieve data from the API. The received data is then converted from JSON to a Python object.

## 2. Data analysis using the Pandas library:
After downloading the data, it is processed using the Pandas library. The data is normalized into a data frame, making data analysis and manipulation easier. The data is then saved to a CSV file so that it can be reused later.

## 3. Automation of data download:
The api_runner() function is designed to automatically retrieve data from the API at a specified frequency. This is done through a loop that calls the api_runner() function and puts the thread to sleep for a specified period of time.

## 4. Data visualization:
Once the data is collected, it is analyzed and visualized using the Seaborn library and Matplotlib. Charts are created to examine price trends for various cryptocurrencies and to analyze price changes for a single cryptocurrency over time.

This project enables the analysis of current trends in the cryptocurrency market and the automation of the process of collecting and processing data, which may be useful for people following financial markets. Additionally, it allows you to save data to CSV files, which allows you to later analyze the collected historical data.
