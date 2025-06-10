# Netflix Content Dashboard (Tableau Project)

This Tableau project explores Netflix's global content catalog through a comprehensive dashboard. The dashboard provides visual insights into trends across content type, geographic distribution, audience ratings, and movie durations using publicly available Netflix metadata.

---

## Objective

To design an interactive dashboard that enables exploration of:

- Distribution of content between movies and TV shows
- Growth of Netflix's catalog over time
- Country-level contributions to content availability
- Audience rating trends by region and globally
- Genre diversity and typical content durations

---

## Tools and Technologies

- Tableau Desktop
- Dataset: Netflix Titles Metadata (`netflix_titles.xlsx`)
- Visualization Techniques: Bar charts, treemaps, bubble plots, line graphs, histograms, boxplots

---

## Key Insights

### Content Distribution
- Movies outnumber TV shows by more than 2:1 in Netflix's library.
- Catalog growth accelerated between 2014 and 2019 before declining in 2020.
- The United States, India, and the United Kingdom are the leading content contributors.
- The most frequent genres include International Movies, Dramas, and Comedies.

### Geographic and Content Type Trends
- The United States and India contributed the most titles, with significant growth through 2019.
- Countries such as Japan and South Korea have a higher concentration of TV shows, while the U.S. and U.K. offer more movies.
- The U.S. exhibits the highest genre diversity, followed by Canada and India.
- Audience ratings are largely associated with movies, especially TV-MA and PG-13.

### Audience Ratings and Duration
- TV-MA is the most common audience rating globally.
- Movies on Netflix typically fall within the 90 to 100-minute duration range.
- Due to structural differences in how durations are recorded, TV shows were excluded from duration comparisons.

---

## Data Source

**Netflix Titles Dataset**  
Available on Kaggle: [https://www.kaggle.com/datasets/shivamb/netflix-shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
The dataset includes metadata such as title, type, genre, country, cast, release year, rating, and duration.

---

## Repository Contents

| File Name | Description |
|-----------|-------------|
| `netflix_content_dashboard.twbx` | Tableau packaged workbook containing the full dashboard |
| `netflix_titles.xlsx` | Source dataset used for the analysis |
| `dashboard_content_overview.png` | Image export of the content distribution section |
| `dashboard_geographic_trends.png` | Image export of geographic and genre-based insights |
| `dashboard_ratings_analysis.png` | Image export of audience ratings and duration analysis |
| `README.md` | Project documentation and summary of insights |

---

## License and Usage

This project is provided for academic and portfolio use only.  
Reproduction, reuse, or redistribution of materials without permission is not allowed.

---

## Author

**Shalini Chhetri**  
MS in Business Analytics  
The Peter J. Tobin College of Business, St John's University, Queens, NY
