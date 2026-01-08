# Amazon Prime Dashboard Analysis - Power BI

## Overview
A Power BI dashboard analyzing Amazon Prime video content, including shows, movies, genres, release trends, and regional distribution.

## Project Description
An interactive dashboard that analyzes Amazon Prime's vast content library through comprehensive visualizations and metrics. The project transforms streaming data into actionable insights about content distribution, popular genres, release patterns, and viewer preferences across different regions.

## Features
- Content catalog overview
- Genre distribution analysis
- Release year trends
- Country-wise content availability
- Movie vs TV show comparison
- Rating and duration analysis
- Director and cast insights
- Content addition timeline

## Technology Stack
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Amazon Prime dataset

## Dashboard Components

### Key Performance Indicators
- Total Titles
- Total Movies
- Total TV Shows
- Countries Covered
- Genres Available
- Rating Distribution

### Visualizations
- Content type breakdown (pie/donut chart)
- Genre popularity (bar chart)
- Release year timeline (line chart)
- Geographic distribution (map)
- Rating distribution (column chart)
- Top directors and actors
- Content addition trends

### Interactive Features
- Content type filter (Movie/TV Show)
- Genre selector
- Country filter
- Release year slicer
- Rating filter
- Search by title

## Installation

```bash
git clone https://github.com/Ropriya/Analysis-Amazon-Prime-Dashboard-Power-BI.git
cd Analysis-Amazon-Prime-Dashboard-Power-BI
```

1. Open Power BI Desktop
2. Open the `.pbix` file
3. Refresh data connections
4. Explore using interactive filters

## File Structure
```
Analysis-Amazon-Prime-Dashboard-Power-BI/
├── Amazon_Prime_Dashboard.pbix
├── data/
│   └── amazon_prime_titles.csv
└── README.md
```

## Key DAX Measures
```DAX
Total Titles = COUNTROWS(Prime[Title])
Total Movies = CALCULATE(COUNT(Prime[Type]), Prime[Type] = "Movie")
Total Shows = CALCULATE(COUNT(Prime[Type]), Prime[Type] = "TV Show")
Avg Duration = AVERAGE(Prime[Duration])
```

## Dashboard Pages
1. **Overview**: High-level content statistics
2. **Content Analysis**: Movies vs TV shows breakdown
3. **Genre Insights**: Popular categories and trends
4. **Geographic Distribution**: Content by country
5. **Timeline**: Release year and addition patterns

## Key Insights
- Most popular content genres
- Content addition trends over years
- Regional content availability
- Movie vs TV show distribution
- Top content-producing countries
- Rating patterns across content types

## Data Source
- Amazon Prime Video dataset
- Contains information about titles, genres, cast, directors, ratings, and release dates

## Requirements
- Power BI Desktop (Free version)
- Windows 10 or later
- 4GB RAM minimum

## Future Enhancements
- Integration with IMDb ratings
- Sentiment analysis from reviews
- Recommendation engine
- Comparison with other streaming platforms
- Predictive content trends

## Author
**Rohit Ranjan**
- GitHub: [github.com/Ropriya](https://github.com/Ropriya)
- LinkedIn: [linkedin.com/in/contact-rohit-ranjan](https://linkedin.com/in/contact-rohit-ranjan)

---

*Explore streaming content through data!* 📺📊