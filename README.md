# ETL-Pipeline

One of the most important things in data science is the ability to construct an ETL pipeline. This is the ability to extract data, transform or clean the data and then load it into a database or data warehouse. In this project, I took NYC housing data from 2020, which had over 30 million records and over 20 columns, cleaned the data and then loaded it into a database on the Google Cloud Platform. I did this by using the Socrata API which allows access for an enormous range of open data sources from governments, non-profit organizations and non-government organizations (NGOs) from all over the world. 

The following code extracts the data and from the URL using the Socrata API. It will then clean certain columns by changing the data type to int. The default data type when data is pulled from a source is 'string'. The code also parses the dates in the 'latest_action_date' column. Afterwards the code will make each record into a last to finally be loaded through the SQL queries for table creation. 

Here is the code:

![socrata method](https://user-images.githubusercontent.com/71915516/151718061-b2de59b6-4ec1-4421-b3ca-1778553436c9.png)


Here is the output of the code:

![Screenshot (151)](https://user-images.githubusercontent.com/71915516/151718144-c9afe52c-38cd-4086-82ae-40a41850324d.png)


