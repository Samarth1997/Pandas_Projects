📊 Anime Dataset Analysis with Pandas

This project performs feature extraction and exploratory data analysis (EDA) on an anime dataset using Python and pandas.It demonstrates how to extract structured features from semi-structured data (like the episode count and airing date range), and how to derive useful insights like top-rated anime, longest-running anime, and more.

📁 Dataset

The dataset used is anime.csv, which contains anime information scraped from an anime database website (e.g., MyAnimeList). The key columns include:

Rank: Overall ranking

Title: Title of the anime, including metadata like episode count and airing dates

Score: Average rating

Title (embedded metadata):

Episode count

Airing time period (start and end date)

📈 Key Insights

✅ Anime with the Highest Score:

Fullmetal Alchemist: Brotherhood with a score of 9.10

✅ Top 5 Highest Rated Anime:
Extracted using sorting on the Score column.

✅ Anime with the Highest Episode Count:

Gintama with 201 episodes

✅ Longest Airing Anime:

Ginga Eiyuu Densetsu (Legend of the Galactic Heroes), aired for 111 months

🧠 Tools & Libraries

Python 3.12

Pandas

NumPy

Dateutil (for parsing dates)

Jupyter Notebook / Python script
