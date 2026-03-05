# Netflix Content Strategy Analysis | Tableau Dashboard

This Tableau dashboard provides an interactive analysis of Netflix's content catalog from 2008 to 2021. It explores trends in movies and TV shows, genres, directors, content ratings, and release patterns, offering actionable insights into Netflix’s content strategy.

The dashboard is fully interactive, allowing users to filter by country, type, ratings, and other attributes.

### View the Dashboard
You can interact with the dashboard here:  
[Netflix Dashboard on Tableau Public](https://public.tableau.com/views/NetflixShowsAnalysis_17428269753140/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Dataset Used 
- Kaggle Dataset [Netflix Movies and TV Shows (2008-2021)](https://www.kaggle.com/datasets/ariyoomotade/netflix-data-cleaning-analysis-and-visualization/data)
- Time Period: 2008–2021
- Columns Include:
Title, Type, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Genres, and Description.

## Business Questions
This analysis focuses on answering the following questions:
- How has Netflix’s content library grown over time?
- Which countries contribute the most content to Netflix?
- What genres dominate Netflix’s catalog?
- Which directors produce the most content on the platform?
- Are there seasonal trends in when Netflix adds new content?

## Data Preparation
Before building the dashboard, the dataset required several cleaning steps:
- Handling missing director and country values
- Splitting multi-value genre fields
- Converting date fields into usable time formats
- Creating derived variables for release trends

## Visualizations Included
- Content Type Distribution (Pie chart) – Shows the proportion of movies versus TV shows in Netflix’s catalog.
- Top Countries by Content (Map + Bar chart) – Identifies which countries produce the most content for Netflix.
- Top Directors (Bar chart) – Highlights the most prolific directors in the catalog.
- Monthly Additions Heatmap – Shows patterns in when Netflix adds the most content throughout the year.

## Key Insights
- Netflix has been producing more movies than TV Shows in recent years.
- United States, India, and the UK are the top contributors of content.
- The Top 3 Directors dominating content production are Rajiv Chilaka, Raúl Campos & Jan Suter, and Alastair Fothergill.
- Dramas and International Movies are the most viewed genres, followed closely by Documentaries and Stand-up Comedy.
- The highest number of releases occurred in 2019 with 1,422 movies and 591 TV shows.
- Content additions peak in July and are followed by December, likely targeting summer and winter holidays.

## Dashboard Preview

<img width="723" height="718" alt="image" src="https://github.com/user-attachments/assets/c230e2f4-71a3-4cf7-a21c-aaaea7228b32" />


## Interactivity
- The dashboard allows filtering by Year.
- Hover over charts for detailed information.
