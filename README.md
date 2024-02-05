# excel_portfolio_project_2
Analysis of Movies data. This excel project answers a few questions about the film industry by analyzing data about movies from the 1980s up to 2020. Some of the topics discussed are gross revenus change over time, Do movies with high score make more money?, are there genres that are more profitable? 

here is what i did before starting to analyze the data:
1.	Thinking about duplicate data, name column is the only column that we care about. We would not want to see a movie appearing twice. So using conditional formatting, we can glance at duplicate values ![image](https://github.com/Stivan1999/excel_portfolio_project_2/assets/139000414/fe583eab-3a09-4035-858f-7d65cbbf087b)
However, thinking about this again we can have same movie name appearing twice. It could be a reboot with the same name.

To make sure that we do not have the exact same movie appearing twice, we can use the “remove dup;icates” button in Data tab 
![image](https://github.com/Stivan1999/excel_portfolio_project_2/assets/139000414/406cc4f8-c5cd-4e53-bf3f-3757d42859f8)

2) Looking at the rating column, there are some movies with no rating. I will replace the empty cells with “NA” to indicate that no rating is available. 

3) Looking at the “released column” there are some blank cells. Filtering on those two blank cells, I noticed that two movies (“Saw: The final chapter” and “The Wolfman”) are missing some data such as country, budget, gross, company, and runtime. I decided to delete these two movies. 

4) For the budget and gross columns, I turned the numbers into currencies to better visualize the amounts. 



