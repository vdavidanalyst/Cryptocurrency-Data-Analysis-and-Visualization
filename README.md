# [Project: Cryptocurrency Data Analysis and Visualization](https://th.bing.com/th/id/OIP.L4QeNCp8_xgfsbmkNci59AHaEK?w=322&h=180&c=7&r=0&o=5&pid=1.7)

# Overview:
  This project focuses on retrieving and analyzing cryptocurrency data from the CoinMarketCap API. The data is collected periodically and stored in a CSV file for further analysis. The project involves automating data collection, performing statistical calculations on the data, and visualizing the results using plots.

# Features:
- Data Retrieval: The project uses the CoinMarketCap API to fetch the latest cryptocurrency listings. The data includes details such as cryptocurrency name, price, and percentage changes over different time periods.

- Data Storage: The retrieved data is stored in a CSV file named "API.csv" for future reference. If the file already exists, the data is appended to it; otherwise, a new file is created.

- Automated Data Collection: The project automates the data collection process by repeatedly calling the API every 3 minutes for a total of 300 iterations. This ensures that the dataset remains up to date with the latest information.

- Statistical Analysis: The project calculates the mean percentage changes for different time periods (1 hour, 24 hours, 7 days, 30 days, 60 days, and 90 days) for each cryptocurrency. The results are displayed in a tabular format.

- Data Visualization: The project utilizes data visualization techniques to present the findings effectively. It includes a line plot showing the price trend of Ethereum over time and a categorical plot displaying the average percentage changes for different cryptocurrencies.

# Technologies Used:
- Python
- Requests library for API communication
- Pandas library for data manipulation and analysis
- Seaborn and Matplotlib libraries for data visualization

# Conclusion:
This project showcases your ability to retrieve data from an API, automate data collection, perform statistical calculations, and visualize the results, working with real-time data and understanding of the cryptocurrency market.
