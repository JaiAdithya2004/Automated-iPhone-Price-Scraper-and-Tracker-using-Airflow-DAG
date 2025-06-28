#  Flipkart iPhone Price ETL with Apache Airflow

This project automates the end-to-end process of scraping **iPhone prices from Flipkart**, transforming the data to find the **minimum available price**, and **scheduling it with Apache Airflow** to run periodically. The results are saved in a **CSV file** that can be used for analysis or price monitoring.

##  Features

- Web scraping of iPhone listings from Flipkart using `requests` and `BeautifulSoup`
- Transformation logic to calculate **minimum iPhone prices**
- Orchestrated using **Apache Airflow DAG**
- Data is stored in **CSV format** under the Airflow DAGs directory
- Can be extended to send notifications or alerts on price drops



![Screenshot 2025-06-28 154741](https://github.com/user-attachments/assets/ecbe18b4-23fd-4268-949e-2d07cb764bec)


