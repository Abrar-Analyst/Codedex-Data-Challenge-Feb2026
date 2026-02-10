🎵 Spotify Global Music Trends (2009-2025)
📊 The Project Overview
This project explores global music streaming trends over the last 15+ years. By analyzing popularity scores, artist fanbases, and audio characteristics, this analysis aims to identify what makes a track dominate the charts in the modern streaming era.


📂 Dataset Information
Source: Spotify Global Music Dataset (2009-2025) via Kaggle.
Description: This dataset contains comprehensive metadata for thousands of tracks, including popularity metrics, artist follower counts, and specific audio features like energy and danceability.


📈 Visualizations & Key Findings:

1. Genre Popularity Distribution (Box Plot)
Visual: A box plot comparing the track_popularity across the top 10 most frequent genres.
Finding: While mainstream genres like Pop and Hip-Hop show high median popularity, the spread of popularity is remarkably consistent across all top genres. This suggests that Spotify's algorithms effectively surface quality tracks regardless of a specific genre's niche status.

2. Fanbase vs. Chart Success (Scatter Plot)
Visual: A logarithmic scatter plot comparing artist_followers against track_popularity.
Finding: There is a moderate correlation between a large following and high popularity. However, numerous viral tracks exist in the dataset from artists with low follower counts, proving that a massive pre-existing fanbase is not a strict requirement for a global hit.

3. The Artist Evolution (Line Chart)
Visual: A time-series line chart tracking the average track_popularity of a specific artist who is Taylor Swift by release_year.
Finding: This visualization highlights era-based growth. Peaks in the data directly align with major album release cycles and global tours, demonstrating how sustained engagement over years—rather than one-off viral moments—builds long-term chart dominance.

🚀 How to Run
Clone this repository.
Install dependencies: pip install pandas, seaborn, matplotlib.
Run the Jupyter Notebook or Python script to regenerate the visuals.
