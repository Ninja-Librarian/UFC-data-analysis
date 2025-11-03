# UFC-fight-analysis
UFC fight data from 1994 to 2021

The data is about UFC fights between 1994 and 2021. The fights took place all over the world. The data includes physical attributes of the fighters, career statistics, various fight statistics like number of body shots thrown versus number landed and win condition. 	   

Data Source: https://www.kaggle.com/datasets/rajeevw/ufcdata  
The data is sourced from Kaggle and includes a list of every UFC fight from 1994 to 2021.
Every row contains information about both fighters, fight details, and the winner. Such as
the height, weight, and age of the fighter. Fight details include number of body strikes
landed, number of submission attempts, and number of knockdowns among others.
Link to data on Kaggle: UFC-Fight historical data from 1993 to 2021

Data Collection
The data was scraped from ufcstats website using beatifulsoup. Pandas was used to
process the data.
Data Limitations
• Data is from 1994 – 2021
• How the data was originally collected is unknown so there may be inaccuracies.
• A lot of values are missing

Why this data?
Because UFC is cool and finding my own data was really hard.

Ethical Considerations
The names of real people are included in the data. The data is part of open-source
information found on the fighters so it may not be a big issue.

Questions to Explore
• Average age of winners
• Differences between weight classes in terms of different styles of fighting
• Win count for different stances
• Standing strikes vs ground strikes

Data Cleaning Summary
• Missing values
o 106,494 total missing values
• Duplicates: 0
• Timeliness: 1994 - 2021
• Irrelevant columns: none
• Data types
o Int64
o Float64
o Object
o Bool 
