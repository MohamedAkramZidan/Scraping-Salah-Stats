# Mohamed Salah Premier League All Seasons Stats
This project scrapes, processes, and consolidates Premier League match data for Mohamed Salah from FBref.com across multiple seasons.

✅ Project Summary
Collected detailed match statistics for Mohamed Salah from the 2017–2018 to 2024–2025 seasons.

Used pandas to read structured match tables directly from the FBref player page.

Saved the raw season-wise stats as .csv files.

Cleaned each dataset:

Removed extra header rows and unnamed columns.

Added season labels to each row.

Dropped empty or irrelevant columns like "Match Report".

Combined all per-season .csv files into one master dataset.

Saved the final result as a clean .csv file for further analysis.

📁 File Organization
Individual season files saved as:

Mohamed-Salah_MathStat17_18.csv

Mohamed-Salah_MathStat18_19.csv

...

Mohamed-Salah_MathStat24_25.csv

Final aggregated file:

Salah-Stat-PrimerLeague.csv

📌 Notes
Data was scraped directly from FBref.

The focus was solely on Premier League matches.

Indexing was set on MatchDay and Season for easier Analysis
