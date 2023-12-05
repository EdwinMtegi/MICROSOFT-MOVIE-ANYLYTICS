# MICROSOFT-MOVIE-ANYLYTICS
## OVERVIEW                    
Microsoft, a tech giant that wants to venture into the entertainment industry, needs strategic moves to establish a new movie profitable studio. To achive the success  of film production, Microsoft aims to leverage the power of exploratory data analysis. The main goal of this project is to explore key insights into the factors influencing the success of movies at the box office. By comprehensively understanding the current cinematic landscape, the head of Microsoft's new movie studio can make well-informed decisions about the types of films to produce, enhancing the chances of a successful entry into the movie production domain.
## Business Understanding
The main aim of this project is tackling Microsoft's key challenge that is; a lack of expertise in the cinematic business world. The main business issue revolves around understanding what types of movies connect with audiences and leads to success at the box office. The goal of this analysis is to provide Microsoft with valuable insights that can inform its entry into the movie production business. The main players in this venture, especially the Head of Microsoft's New Movie Studio, are eager to gain practical knowledge that will shape the studio's choices and boost its competitiveness in the ever-changing cinematic world.

## Data understanding 
The analysis of this projet results are derived for several databases and files, including Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers. The core of the data anysis lies in the zipped SQLite database (im.db.zip) with  tables such as movie_basics and movie_ratings, while a compressed CSV file (bom.movie_gross.csv.gz) contains valuable information on box office gross income. Navigating through this datasets requires careful consideration of relationships, with a keen focus on how the IMDB data intertwines with other datasets and how different tables related to one another, that is the different primary and foreign keys. Data exploration and analysis involved data cleaning, preparation, and visualization techniques to show insights that directly address the business problem.
## Data preparation and Analysis
The initial step involves cleaning the data that is; ensuring that the data is uniform without missing data which ensures its readiness for analysis. Moving into the analysis, using sqlite3 commands, the project shows different crucial findings derived from exploratory data analysis. This analysis includes; ditribution of movies over the past years, top grossing movies and highest rated type of movie genre. This section not only showcases the depth of understanding gained from the data but also lays the foundation for the recommendations that directly align with Microsoft's aspirations in the movie production business.
## Data Visualization
The project analyzes different aspects of cinematic universe, that is; distribution of movie production over the years, ditribution of movie genre, genre with highest average rating, movie studio with the highest grossing income and top movies with highest profits. 

![Alt text](image-4.png)
The chart shows that the most produced movie genre was documentary while the least as western genre.

![Alt text](image-5.png)
This plot displays the relationship between genres and movie ratings. It shows that group mix, comedy documentary and fantasy had the highest average rating, while drama fantasy and war having the lowest average rating. However, there is a stiff competetion between the genres in that most have the same ratings.

![Alt text](image-6.png)
This plot visualizes the top 10 movies by total income. There is a stiff competition between the top 10 movies with the highest having $1.5 billion dollars. It is keen to note that the top movies are majorly of adventure and fantasy genre.

![Alt text](image-7.png)
This plot shows the relationship between movie studios and gross income. P/DW studio ranked top, while PW and Uni followed. Among the top 50 studios includes Sony, Fox, WB and Hc 

![Alt text](image-8.png)
This plot displays the correlation between movies and total profits. Avatar movie ranked on top.

![Alt text](image-9.png)
This plot shows the distribution of movie production over a number of years. It shows that movie production increased gradually from 2010 t0 2016 and experienced a sharp decline to 2020.2016 had the highest number of movies while 2020 had the lowest number of movies. It is however wise to note that the sharp decline might have been as a result of unforeseen factors, i.e Corona pandemic.

**BUSINESS RECOMMENDATIONS**

**Genre Selection for New Movies:

Microsoft should consider focusing on genres that have shown popularity and resilience, such as documentary and fantasy. Movies that entails a mix of action,adventure and fantasy have proved to be the highest grossing films. However, they should also consider exploring opportunities in genres that are less saturated, like westerns, so as to capture a niche audience.

**Optimizing Movie Runtimes:

The average and median runtime findings suggest that audiences generally prefer movies with a runtime around 86-87 minutes. Microsoft should aim to produce movies within this range so as to align with viewer preferences and also maximize engagement

**Content Quality and Ratings:

Microsoft should prioritize in creating high-quality content, as shown in the average movie ratings. This can be achieved focusing on engaging storylines, skilled production, and effective marketing strategies.

**Strategic Partnerships and Franchise Development:

The success of movie franchise like "Marvel's Avengers" and "Avatar" suggests that  partnerships and potential franchise opportunities can significantly impact box office performance and profits. Microsoft should consider collaborations with established franchises or invest in developing its own franchises to drive long-term success. Microsoft should also consider patnership with movie studios like BV, WB and P/WD which had the highest movie gross income.

**Profit Maximization Strategies:

Microsoft should study the success factors behind high-grossing movies like "Avatar" and incorporate those elements into its own productions. This may include investing in top-tier talent actors, innovative storytelling, and effective marketing campaigns to maximize profits.

**CONCLUSION**
These recommendations aim to guide Microsoft in making informed decisions based on the insights derived from the exploratory data analysis. It's essential for Microsoft to adapt these recommendations to their specific goals, resources, and market dynamics. Additionally, monitoring and adaptating industry trends is very crucial for long-term success in the movie production business.
