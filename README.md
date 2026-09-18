# Situation

A consulting company has a lack of consolidation of the financial data that already exists which makes it difficult for the financial team to compare financial performance across different countries and service lines. 

# Task

My task is to create a dashboard in excel which displays the consolidated financial information at the location and service line level. The dashboard would allow management to identify where performance differs significantly and decide what action to take. 

# Action

<img width="1378" height="654" alt="image" src="https://github.com/user-attachments/assets/4b24c773-b576-486b-bc7e-e6b6c4e82c8d" />


I produced a dashboard on excel which contained 5 visualisations. The first visualization displayed the revenue by country through a map. The second visualization compared revenue and EBITDA through the years 2018 to 2027, which can be further filtered with customer and service type. The third visualization displays the profit and EBITDA margin via a pie chart, which can be filtered by consumer, service, and year. The fourth visualization is a bar chart, which compares the revenue, gross profit, and EBITDA across the service types in the dataset. The fifth and final visualization is an EBITDA bridge, which can be filtered by consumer type, service, and year.  

I used the VLOOKUP function to retrieve the gross profit and EBITDA percentage. The INDEX function was used to extract the revenue and within the INDEX function the MATCH function was used to generate indexes to identify the relevant rows and columns. After the VLOOKUP and INDEX functions were used to retrieve the gross profit percentage, EBITDA percentage, and revenue I calculated the gross profit and EBITDA.

I then created pivot tables to summarise the financial data and then created visualisations to compare revenue, gross profit and EBITDA. The dashboard makes it easier to identify any stark differences in revenue, gross profit and EBITDA throughout the years.

# Result

The second visualization in the dashboard revealed that revenue and EBITDA drastically decreased in the years 2023 to 2024, and it increased in the years 2024 to 2025. It would be useful for the financial team to investigate why revenue and EBITDA was really low in 2024. One possible explanation of why EBITDA and revenue went back up in 2025 is that the accounting, AI, and marketing services were bringing a substantial amount of revenue as compared to 2024, where marketing was the only service that was bringing substantial revenue. Another explanation is that the profitability that marketing brought in 2023 was around 250K dollars and decreased drastically to 200K dollars in 2024.
The dashboard would help the financial team investigate any substantial differences in finances across the service line, customer type, and country level. Additionally, the dashboard will help upper management in making strategic decisions on where to invest, which services to expand, and which areas of business need further investigation.

