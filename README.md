# Amazon-prime-movie-data-analysis

## My First Microsoft Excel Dashboard at Edge line Careers Data Analysis Professional (DAP) Class

# INTRODUCTION
The dataset is for the analysis on the customer behavior, trends and pattern of AMAZON PRIME MOVIES from the year 1920 to 2021. Amazon prime video is an American subscription video on demand over top streaming and rental service of amazon offered as part of Amazon’s prime subscription.

# ABOUT THE DATA/DATA COLLECTION
The dataset was gotten from [Ganiyat Olajumoke Ajala](https://www.linkedin.com/in/ganiyat-olajumoke-abe). It is a structured data, and it is a secondary data collected. The data contains a table in csv files. It contains 9668 rows and 13 columns.
The analysis to be carried out is to answer the following questions;
1.	What are the top 10years with the highest release?
2.	What are the top five movies according to viewer’s rating?
3.	What is the disparity or proportion in percentage between the types?
4.	What are the top five main genres from 1920-2021?
5.	What are the top five main cast from the year 1920-2021?
   
# TOOLS
The tool used is Microsoft excel for analysis and using power query editor for data cleaning.

# DATA CLEANING AND TRANSFORMATION
The following are the different cleaning procedures;

•	The data contained blanks and 2 duplicates which was removed

•	The Listing 1 was divided using split column by delimiter to the left by comma and was renamed ‘main genre’ also used for country which was named ‘main country’ and finally for cast which was named ‘main cast’

•	Renamed the Rating .1 to ‘Viewer Rating’

•	The year was changed to Text format

•	The blanks in rating was replaced with ‘Not defined’, for Country ‘Unknown’, for rating ‘null’ and for release year ‘not stated’ using the find and replace tab. Then made used of close and load into excel for further analysis.


# EXPLORATORY DATA ANALYSIS(EDA) AND INSIGHT
For the analysis to be understood and the questions to be answered pivot tables were created for it to properly analyzed for insights. The following consist of questions, its analysis and insight for each;

1.	What are the top 10 release years of shows?

A pivot table was created having the fields ‘release year’ and ‘show-id’. The function ‘count’ was used to get the total count of the show id per year and the top 10 years was selected using the ‘value filter’. The Pivot table showed that the Top 10years was ranging from years 2011-2021, with 2021 having the highest show with 6601 shows. It showed that years 2011 and 2012 was static i.e., there was increase nor decrease. And as the year progressed there is increase in the shows.


![question one](https://github.com/Deborah-Marizu/Amazon-prime-movie-data-analysis/assets/147628427/5633d41b-7ab9-4721-83a2-7cfe06df8e73)


The image above is the line chart created to show the trend from the years 2011 to 2021.

2.	What are the Top Six movies according to viewer’s rating?

A pivot table was created having the fields ‘title’ and ‘viewer’s rating’. The function ‘Sum’ was used to get the total of viewer’s rating. The Top six movies were selected using Value filter. The pivot showed the Top six movies, noting that the ‘Song of Texas’ and ‘Snow white’ has similar sum of Viewer’s rating of ‘17’ and it being the highest sum and also there is a similarity between ‘Infidelity’ and the ‘Squid and the Whale’ of the value ‘13’

![question two](https://github.com/Deborah-Marizu/Amazon-prime-movie-data-analysis/assets/147628427/ff046d44-d85c-4001-8395-969a4d97a58e)

 
A clustered column chart was created to show the Viewer’s rating from the highest six to the lowest six.

3.	What is the proportion of the Movie type to Tv show?

A pivot table was created having the fields ‘type’ and ‘show id’. The function ‘Count’ was used to get the total count of show id according to the ‘type’ that is TV shows and Movies. The Pivot table showed that the years from 1920 to 2021, the total count was 7814 and TV Show was 1854 having the percentage 81% and 19% respectively. There is a higher percentage for Movies to the TV Shows.

 ![image](https://github.com/Deborah-Marizu/Amazon-prime-movie-data-analysis/assets/147628427/e1371e8f-f6d3-4415-a6d1-f0abc9137460)


A pie chart was created to show to show the disparity and proportional relationship between TV Shows and Movies over the years.

4.	What are the Top five main genre?

A pivot table was created having the fields ‘Main genre’ and ‘show id’. The function ‘Count’ was used to get the total count of show id in respect to the ‘main genre’. The top five main genre was selected using the Value filter. The pivot table showed the Top five main genre includes; Horror, Documentary, Comedy, Action and Drama as the top five main genre. The highest five was drama with 2216 Show id and the lowest five is Horror with 535 show id.
 
![image](https://github.com/Deborah-Marizu/Amazon-prime-movie-data-analysis/assets/147628427/fd3c2032-6c23-49ad-9c06-db38af0e7c36)

A Bar chart was created to show the relationship amongst the top five main genre using the total number count of the show id. 

5.	What are the Top five main cast from the year 1920 to 2021?

A pivot table was created having the fields ‘Main Cast’ and ‘show id’. The function ‘Count’ was used to get the total count of show id in respect to the ‘Main Cast’. The top five main genre was selected using the Value filter. The pivot table showed the Top five Main Cast, with the value “Unidentified” being the highest with 1249. It can be seen that there are errors with the Column Main Cast has, its blanks which was earlier replaced with “Unidentified”.

![image](https://github.com/Deborah-Marizu/Amazon-prime-movie-data-analysis/assets/147628427/07f7e6fa-9a31-4223-9954-1e60164a4cdd)

 
The Bar chart was created to show the top five Main Cast. The chart showed the highest bar was ‘Unidentified’ and a bar having a figure 1 which inevitably showed this question has an Unfair and biased analysis.


# Visualization

![prime video analysis dashboard 1](https://github.com/Deborah-Marizu/Amazon-prime-movie-data-analysis/assets/147628427/0e78a601-ad58-4b5a-ad39-782542e5b94c)

# RECOMMENDATION

It's a great observation that there's a significant difference in the production of movies and TV shows on Amazon Prime Video. Balancing the content library between the two types can indeed provide a more comprehensive view of customer preferences and behaviors. By producing more TV shows, Prime Video could potentially reduce the bias and better cater to a wider audience. It's important to analyze viewer data and preferences to make informed decisions in content production.

