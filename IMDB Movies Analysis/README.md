# Entertainment Industry Analysis — Trends, Genres & Audience Targeting

[![Kaggle](https://img.shields.io/badge/Kaggle-00838F?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/code/ashishjangra27/imdb-movies-analysis)

**Overview:** An end-to-end analytical exploration of the IMDb movie dataset to quantify the evolution of global cinema and television. This project tracks production volume, genre dominance, and the shift between family-friendly and adult-oriented content from the early 1900s through the digital and streaming eras.

## Workflow
1.  **Ingest** — Load the raw IMDb dataset containing titles, ratings, genres, and certification details.
2.  **Data Cleaning** — Standardize movie names, convert durations to integers, and clean vote counts for numerical analysis.
3.  **Temporal Parsing** — Utilize Regular Expressions (Regex) to extract `start_year` and `end_year` from complex string formats to distinguish between standalone movies and multi-year series.
4.  **Identity Mapping** — Harmonize Director and Star IDs/Names, handling "Anonymous" entries and exporting cleaned mappings to JSON for external use.
5.  **Industry Trend Mapping** — Visualize the year-over-year growth of content production, identifying historical milestones like the 1950s industry expansion and the post-2000 content boom.
6.  **Format Comparison** — Contrast the production trajectories of "Movies" vs. "TV Series" to observe how digital scale and streaming have influenced format preferences.
7.  **Dynamic Genre Analysis** — Generate animated bar chart races to track the rise and fall of genre popularity (e.g., Drama, Comedy, Documentary) over a 120-year period.
8.  **Audience Segmentation** — Categorize dozens of global certifications into three primary buckets: "Kids," "Family," and "Adult" to analyze shifts in targeting strategies.

## Key Insights
* **The 21st Century Explosion**: Content production saw a massive acceleration post-2000, peaking between 2015 and 2019 before a visible post-2020 contraction.
* **Movie Dominance**: While TV series saw significant growth during the "Television Era" (1960–1989), standalone movies remain the dominant content type in terms of total volume.
* **Genre Evolution**: The analysis captures the steady dominance of Drama and Comedy while highlighting the surge in niche genres during the digital expansion era.
* **Adult Content Rise**: Adult-oriented content (R, TV-MA, etc.) has seen a significant increase in production volume and audience engagement (votes) since the 1950s.
* **Engagement Patterns**: While "Kids" and "Family" content provide steady production volume, "Adult" and "Family" categories often drive the highest peaks in total audience voting activity.

## Tech Stack
* **Python**
* **Pandas** & **NumPy** (Data Manipulation)
* **Regex** (Complex String Parsing)
* **Plotly Graph Objects** (Interactive & Animated Visualizations)
* **JSON** (Metadata Storage)

## Next Steps
* **Predictive Modeling**: Develop a regression model to predict movie ratings based on genre, director, and cast.
* **Financial Correlation**: Integrate budget and gross income data to analyze the ROI of different genre-certification combinations.
* **Streaming Influence**: Deep dive into "Streaming Era" (2010–Present) data to identify if platforms favor specific durations or genre clusters.
* **Network Analysis**: Create a graph visualization of director-actor collaborations to identify "power duos" in the industry.
