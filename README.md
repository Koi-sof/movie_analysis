# BOX OFFICE ANALYSIS.

## INTRODUCTION

Our company stands at the precipice of an exciting new venture: the establishment of an original movie studio. In an era where leading enterprises are increasingly venturing into video content creation, this initiative represents a strategic move to diversify our portfolio and tap into an influential market. However, as newcomers to the film industry, a fundamental understanding of what makes a movie successful at the box office is important.

## Business Problem:

We need to identify which factors significantly influence box office performance, so we can invest in the right kind of movie production projects.

## OBJECTIVES:
1. Collect and investigate the box office data.

2. Find out which movie genres have historically performed best.

3. Identify trends in both domestic and international box office.

4. Perform Exploratory Data Analysis (EDA) and identify key attributes that influence box office success.

## Datasets Used:

*im.db* - SQLite DB that contains movie data, ratings, number of votes, etc.

*tn.movie_budgets.csv* - Contains gross revenue and production budget.

## Key Features Analysed:

* Movie Title

* Genre(s)

* Production Budget

* Release Year and Date

* IMDb Ratings

* Domestic and Worldwide Box Office Gross

## Data Preparation and Cleaning.
* Imported libraries such as Pandas, NumPy, SQLite3, and Seaborn to work with datasets.

* Extracted data by unzipping .zip files.

* Loaded structured data using SQLite3 (for .db files) and Pandas (for .csv files).

* Cleaned datasets by handling missing values, removing duplicates, and fixing formatting issues.

* Created new features where necessary (e.g., adding total_gross and profit columns).

## EDA

1. **Uni-variate Analysis**

I examined the distribution of Genres.

2. **Bi-variate Analysis**

I examined relationships between two variables to help identify patterns, relationships or differences between variables; e.g: genre and ratings, genre and production.

3. **Correlation Matrix**

I checked the ralationship among numeric columns in each dataset.

## Visualizations

**Genre by Rating**

<img width="727" height="360" alt="image" src="https://github.com/user-attachments/assets/c51d13b2-fcb3-4ba3-903c-631df50d81ff" />

**Genre by Production Cost**

<img width="802" height="368" alt="image" src="https://github.com/user-attachments/assets/28c8bf12-76d8-4a8d-bb6a-d2234fe67889" />


## Key Insights

Drama and Comedy dominate in frequency thus suggesting a strong audience appeal

Documentary and History received high IMDb ratings reflecting strong reception, critically

Hybrid genres are popular because they combine different storyteling styles effectively

## Conclusion

*Genre Focus*: Invest in producing Action, Adventure, and Family-oriented films as they are highly popular and financially rewarding.

*Smart Budgeting*: Allocate production budgets carefully to balance quality and profitability.

## Tableau Dashboard

https://public.tableau.com/views/movie_analysis_f/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
