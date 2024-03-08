# INTRODUCTION


Project documentation for the police recorded crime data tables from March 2013 to June 2023 aims to provide comprehensive insights into the trends, patterns, and analysis of crime data across various police force areas. The documentation will include details such as methodology, data sources, data cleaning processes, data modelling, visualizations, and recommendations. It will serve as a valuable resource for stakeholders, policymakers, researchers, and the general public to understand and address issues related to crime prevention and law enforcement strategies.

# PROBLEM STATEMENT


Introduction
In today's world, crime rates have surged, posing complex challenges for law enforcement globally. To tackle these issues head-on, the integration of advanced technologies and data analysis is crucial. This case study delves into how crime data analysis can elevate the effectiveness of law enforcement in a major city.

Client Profile:
Our client, a big-city police department, is grappled with escalating crime rates and in need for a more proactive crime prevention strategy. The client reach out to Datafied Technologies to seek expertise to leverage data analytics to gain insights into crime patterns, potential crime hotspots, and develop targeted strategies for crime reduction.

Your Task
You are a junior data analyst at Datafied Technlogies. You are required to harness the power of data analytics to:

1. Identify and understand crime patterns and trends.
2. Identify potential crime hotspots based on data-driven insights.
3. Enhance proactive crime prevention strategies.


Data set information
The 'Police recorded crime open data tables, year ending March 2013 onwards' release is a top-tier statistical output adhering to professional standards. Produced by Home Office statisticians, it ensures objectivity and complies with the Code of Practice for Statistics.

For further details on the data table specification, consult the data dictionary document.

The successful execution of this project will empower the police department to make informed decisions, leading to a substantial improvement in crime prevention and law enforcement effectiveness. This not only transforms traditional policing methods but also underscores the significance of a proactive, data-driven approach in addressing the evolving challenges of crime in urban environments.

 Data Source: [Criminal record]https://docs.google.com/spreadsheets/d/1PmfXCD1m5srDAy5Xqd5zSIqNyQc6oL-fu5Whtz_Uwdc/edit?usp=classroom_web&authuser=

 # PREPROCESS DATA 

 The data was cleaned by creating the year column from the financial year column, creating a quarter- year column by combining the financial quarter column and newly created year column. and i also created a financial mon th column

# Data before cleaning![Screenshot 2024-03-05 162721](https://github.com/Annie15555/Annie15555/assets/157610325/9663e848-6be2-458d-ae8d-c70733672b6c)
# Data after cleaning![Screenshot 2024-03-05 172411](https://github.com/Annie15555/Annie15555/assets/157610325/115fd740-d2af-4534-b87d-90e187c410c2)


# DATA MODELLING AND RELATIONSHIP

Dimension: new tables for identified dimensions where created

-Offence table

-Date table 

-Location table

The data model was designed using the Star Schema where the different dimensions were connected to the Facts table in a one-to-many relationship.

![Screenshot 2024-03-05 173830](https://github.com/Annie15555/Annie15555/assets/157610325/94566964-97c8-4e64-9d28-c8b5915db592)



