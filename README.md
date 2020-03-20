# Regarding Phase 1 (shreyak_proj_phase1.ipynb)
## Things to Install:

- run the following before running webscraper: <br/>
  python3 -m pip install --user html5lib <br/>
  python3 -m pip install --user lxml <br/>
  python3 -m pip install --user bs4 <br/>
 
 ## Datasets Used
 
- Academy Awards nominees and winners
- IMDB Top Rated 250 movies 
  
 ## What the Web Scraper Does:
 
 It gather information regarding IMDB's top rated 250 movies (reviews, movie length, movie rating, genre, release date, summary, director, writer, stars, keywords, budget, gross USA profits and production company) by crawling through each movies individual page on IMDB. The notebook then cleanses the data by eliminating common inconsistencies. All that information is then concatenated into a singular data frame and composed into a CSV file. The other dataset contains information regarding the Academy Awards over the years -- it was directly downloaded via datahub.io. 
 
 # Regarding Phase 2 (shreyak_proj_phase2.ipynb)
 ## Things to Install:

- No additional installations necessary. Simply run all cells in Jupyter Notebook.
 
 ## Datasets Used
 
- Academy Awards nominees and winners
- IMDB Top Rated 250 movies 
  
 ## EDA Process
 - The analysis of the data is included after each graph/chart under the "Analysis" section. There are 3 scatterplots, 2 bar charts, 1 stacked bar chart, 1 histogram and 1 plot line.
 
 # Regarding Phase 3 (shreyak_proj_phase3.ipynb)
 ## Things to Install:
 - No additional installations necessary. Simply run all cells in Jupyter Notebook.
 
 ## Datasets Used
 - IMDB 1000 movies from 2006 to 2016
 
## Questions Explored:
- Does a high number of votes, a high revenue and a high metascore correlate to a high rating?
- Can an accurate rating for a specific movie be predicted by taking the average rating of the 10 movies most similar to it with regards to popularity and genres?

## Answers to Questions:
- A high number of votes and a high metascore do correlate to a high rating, revenue not so much. This was validated via linear regression and pearson coefficients.
- Yes, an accurate rating can be predicted using this method. This was validated via the K-NN algorithm. My algorithm underpredcits. To improve the accuracy we could explore adding features or adjusting the K-value.

## Summary of Analyses:
- Written in notebook under analyses sections. An explanation of process is also included in notebook.


 
