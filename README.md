# Movies-ETL Pandas to SQL

## Overview of Project
The biggest online merchant, on the globe, Amazing Prime, also has a streaming platform. This streaming platform is called Amazing Prime Video. The company wants an algorithm created that will predict which low-budget flicks will be gain wide-stream popularity so they can grab the streaming rights at a low cost. They decided to have a hackathon to not only inspire their team, but to build on connections with the local coding community. Britta an Amazing Prime Video employee has been asked to create datasets for the hackathon. One of the datasets is a data scraped from the Wikipedia website, the other is data pulled from Movie Land's website on rating data. Britta will complete the Extract, Transform and Load (ETL) process on this data by extracting from the Wikipedia and Movie Lens websites, making it one table (transforming it), and turning it into an SQL table (loading it). Amazing Prime Video loved the new data set that Britta created and wants it updated daily. You and Britta will be using the ETL process on the SQL table Britta created so that it updates daily. It will now include data from Wikipedia, Kaggle and Movie Lens.

### Purpose
Create a clean database for a hackathon using three csv files that will update daily. The idea is that the hackathon will encourage the team but create networks with the local IT community. 

## Analysis
There are 6,052 rows in the movies table and 26,024,289 rows in the ratings table. This can be seen in the screenshots below. Detailed screenshots of the table information are provided the Challenges and Difficulties Encountered section.

### Screenshots

#### Movies Query

![movies_query.png](https://github.com/AprilVilmin/Movies-ETL/blob/main/movies_query.png)

#### Movies Query Results

![movies_query_results](https://github.com/AprilVilmin/Movies-ETL/blob/main/movies_query_results.png)

#### Ratings Query

![ratings_query.png](https://github.com/AprilVilmin/Movies-ETL/blob/main/ratings_query.png)

#### Ratings Query Results

![ratings_query_results.png](https://github.com/AprilVilmin/Movies-ETL/blob/main/ratings_query_results.png)

## Challenges and Difficulties Encountered
This was the most difficult module for me to date. I could not share my csv files on my GitHub as they were too large, so I took a screenshot of the select * statement results for both the ratings table and the movies table in pgAdmin and saved them in the Resources folder. I also ran into an issue when trying to use the 'Hint' provided in section of the challenge. When I changed the code from section three from to 'replace' as the hint suggests, the wrong number of rows returned. The way I was able to obtain the correct number of rows in my GitHub was to delete both existing tables (movies and ratings) from pgAdmin and then run my code. I have included a screenshot of the hint below. 

### Screenshots

#### pgAdmin Movie Table Screenshot

![Movie Results.png](https://github.com/AprilVilmin/Movies-ETL/blob/main/Resources/Movie%20Results.png)

#### pgAdmin Ratings Table Screenshot

![Ratings Results.png](https://github.com/AprilVilmin/Movies-ETL/blob/main/Resources/Ratings%20Results.png)

#### Hint Screenshot
![Hint.png](https://github.com/AprilVilmin/Movies-ETL/blob/main/Hint.png)

