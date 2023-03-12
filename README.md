+ ## Overview
  The Microsoft company  is looking to venture  in the movie industry by establishing a new movie studio  but they have no prior experience in making movies. They need to understand  what types of films are doing well at the box office to make informed decisions  on what type  of films they should create . The objective is to identify the most succesfull types of films in the current market and provide actionable insights  to help Microsoft make decisions  that will increase their chances of success. To achieve this goal ,data on box office performance and movie characteristic s will need to be collected , cleaned and analyzed to indentify trends and patterns .The insights generated from the analysis  can be used to make informed decision making process.

+ ## Business Understanding 
  + Microsoft wants to enter a highly competitive movie industry and establish a new movie studio but the lack experience  in creating movies . They need to understand  what types of films are popular and successful currently  on box office . This understanding will help Microsoft to make better decisions on what types of films they should create to increase their chances of success . The goal of the project is to provide insights on the current trends in the movie industry and identify movies doing well at box office . This analysis will enable Microsoft make data driven decisions on what type of movies they should make to increase their chances of  being successful.

+ ## Data understanding and analysis
  + source of data
    The movie data was collected from various  sources and available in the folder zipped data.It includes datasets from box office mojo,IMDb,Rotten tomatoes, The movieDB,and The Numbers.The data files have different formats , including compressed CSV,TSV and SQLite database files.
    To make the analysis less challenging we will use the following data files :
    1. im.db.zip:This is a zipped SQLite database file that  contains       relevant data from IMDB.The  movie _basics and movie _ratings tables are the most relevant in our analysis
    2. bom.movie_gross.csv.gz.This is a compressed csv file  containing data on movie box office gross earnings .It can be opened using pd.read_csv  without expanding the file                        

  + Description of data
    The data understanding of this project involves Identifying and acquiring relevant data that can be used to gain insights into this movie industry . The data will be cleaned and analyzed to identify trends and patterns  that can help Microsoft understand what types of films are performing well at the box office. 
   The data required for this project may include box office data , movie characteristics such as genre , budget , release date , and ratings as well as data on marketing strategies  and audience demographics .This data can be sourced from various publicly available datasets such as  IMDb , Box office mojo and  The numbers.
   The data will be cleaned to ensure that it is accurate ,complete and consistent . This may involve in removing duplicates ,correcting errors and filling missing values . Once the data is cleaned it can be analyzed using statistical techniques to identify trends and patterns . The insights provided from the data analysis will help Microsoft what type of films are successful in box office and inform the decision making process  for the new movie studio                                                   
  
  + Visualizations

   Movie count by region

    ![plot](./data/Screenshot%202023-03-12%20232344.png)

   movie count by region and language

 
    ![plot](./data/screenshot%202023-03-12%20232544.png)

    Relationship between frequency and rating

     ![plot](./data/screenshot%202023-03-12%20232736.png)

+ ## Conclusion
Based on the project overview, the goal was to use exploratory data analysis to identify the types of films currently doing well at the box office, and translate those findings into actionable insights for Microsoft's new movie studio. The data used was sourced from various websites and databases, including Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers.
  +  Summary of conclusions including three relevant findings
        1.Genre popularity: By analyzing the movie data, it may be possible to identify the most popular movie genres at the box office. This could help Microsoft's new movie studio to target their films towards popular genres and increase their chances of success. For example, if action movies are consistently performing well, the studio may decide to focus on creating action films.
        2.Budget vs. box office success: Finally, it may be worth exploring the relationship between a movie's budget and its box office success. This could help the studio to make informed decisions about how much to spend on production and marketing. For example, if lower-budget films are consistently performing well, the studio may decide to focus on creating more cost-effective films. Alternatively, if high-budget films are driving box office success, the studio may prioritize investing in bigger-budget productions.
        3.Critical acclaim vs. box office success: It may also be interesting to compare a movie's critical reception (based on ratings from sites like IMDB and Rotten Tomatoes) to its box office success. This could help the studio to understand whether critical acclaim is necessary for box office success or whether there are other factors that are more important. For example, if a movie with poor reviews still performs well at the box office, the studio may prioritize marketing and distribution over critical reception.
    


