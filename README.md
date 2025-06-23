# YouTube-trending-video-analytics

## Project Overview
This project analyzes trending YouTube video data from 4 countries (US, IN, GB, JP) to uncover viewer behavior, category popularity, sentiment trends, and regional comparisons. It combines Python-based data processings with Tableau-based dashboard visualizations.

## Dataset
<a href="https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset?select=US_category_id.json"> YouTube Trending Video Dataset (updated daily) </a>- From which data from 4 regions were analyzed

## Tools Used
- **Python (Pandas, Seaborn, TextBlob)** – For data cleaning, transformation, sentiment analysis
- **SQLite (via Python)** – SQL queries for aggregations and ranking
- **Tableau** – To create interactive dashboards and storytelling

## Steps used
1. Cleaned and merged trending data from 4 regions
2. Performed sentiment analysis on titles and tags
3. Calculated trending duration of each video
4. Used SQL queries to rank categories by view count
5. Visualized:
   - Time-series trends
   - Most popular categories
   - Sentiment distribution
6. Designed an interactive dashboard in Tableau

## Files included
<a href="https://github.com/Kavya-Rajeev/YouTube-trending-video-analytics/blob/main/Youtube_trend_analysis.ipynb">Youtube_trend_analysis.ipynb </a>- Jupyter notebook with complete code

<a href="https://github.com/Kavya-Rajeev/YouTube-trending-video-analytics/blob/main/Visualizations_Screenshot.pdf">Visualizations_Screenshot.pdf </a>- Tableau dashboard and charts screenshots

<a href="https://github.com/Kavya-Rajeev/YouTube-trending-video-analytics/blob/main/Youtube%20project%20report.pdf">Youtube_project_report.pdf</a>- 2-page final project report (PDF)
