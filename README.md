Our data science project investigates two Spotify track datasets, covering 125 genres, each track enriched with detailed audio features. These datasets are employed for diverse analyses:

**Exploratory Data Analysis (EDA):** Our EDA reveals significant patterns and insights, essential for guiding further research and applications. It involves thorough data cleaning and analysis, uncovering major findings like the 'Top 10 Popular Artists' and 'Top 10 Popular Tracks,' while also examining correlations among various acoustic features.

**Answering Specific Questions:** We delve into questions about musical preferences, trends, and genre-related characteristics, exploring how these influence song popularity. Insights from this analysis are crucial for:
- **Understanding Audience Trends:** Aiding the creation of music and events that resonate with audiences.
- **Event and Program Planning:** Using knowledge of popular genres to design events that attract more attendees.
- **Enhancing Advertising and Marketing:** Leveraging genre popularity to refine marketing strategies.

**Recommendation System:** We've developed a system that recommends songs by matching audio features and genres, effectively aligning with user preferences and even successfully suggesting Chinese songs in datasets with few such tracks.

**Classification:** Utilizing pyspark in a big data environment, we train models to classify tracks based on audio features and genres. This is useful for genre classification and mood-based categorization for large dataset.

Our tests across varied dataset sizes ensure scalability and reproducibility. Inspired by existing studies and expanding upon them, we’ve adapted our recommendation system for playlists and publicly shared our EDA results. This enhances our understanding of data interactions and improves practical applications in music analytics.

The first 3 tasks are implemented in "Task_by_spotify.ipynb" and "Task_by_dataset.ipynb". The classification task is implemented in "Classification_Task_for_Genre.ipynb". The report for classification task in under "report" folder.