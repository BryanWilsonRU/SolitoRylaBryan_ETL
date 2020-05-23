# ETL Project

- Bryan
- Ryla
- Solito

# Synopsis

IMDB has a list a revered list of the [Top 250 Movies](https://www.imdb.com/chart/top/?ref_=nv_mv_250) based off of user IMDB ratings. As per this IMDB page, shorts, TV movies, and documentaries are not included; also, only movies that received at least 25,000 ratings from users.

Due to the prevalence of streaming services in our media consumption, we wanted to discover which streaming services provide these movies.  We analyzed the available movies for Netflix, Amazon Prime, Disney+, and Hulu for this project.

## Extract

We retrieved a list of the Top 250 Movies along with the movie's year of release and IMDB rating by web scraping the following [page](https://www.imdb.com/chart/top/?ref_=nv_mv_250).

We also scraped the movie pages from (reelgood.com)[https://reelgood.com/movies] to find the movies available on Amazon Prime, Netflix, Disney+, and Hulu. Since you can filter these pages by IMDB rating, we restricted the movies we retrieved to an IMDB rating of 8 or higher in order to easily match movies that are on the IMDB Top 250 list.

WE also were able to retrieve additional information on the movies available on Netflix and Disney+ from Kaggle sources.

