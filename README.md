# Bluesky Scraping NATO Project

This project is dedicated to scraping posts containing the hashtag **#NATO** from the Bluesky socila network. It performs a first hand data analysis by collecting, processing, and visualizing posts in order to helps identify trends and popular hashtags in the online discourse surrounding NATO. Is is mostly an unstructured data analysis based on both words from the posts and from the hashtags commonly used with NATO's.

## Features

- **Data Scraping**:
  - Extracts posts containing specified hashtags ( '#NATO`) using Bluesky API ([At Protocol](https://atproto.com/)).
> **Note:** Due to the API's restriction I could only scrape the latest 9 856 posts

- **Data Processing**:
  - Identifies hashtags, URLs, locations, and other key metadata from the posts.
  - Cleans and preprocesses text for further analysis.

- **Visualizations**:
  - Generates a **wordcloud** to highlight frequently used terms in posts.
  - Creates **bar charts** to show top hashtags realted to NATO.
  - Develops a **line chart** for the daily count of posts.

---

## Technologies Used

- **Languages**:
  - Python

- **Libraries**:
  - [Pandas](https://pandas.pydata.org/) - Data manipulation and analysis
  - [Matplotlib](https://matplotlib.org/) - Data visualization
  - [WordCloud](https://github.com/amueller/word_cloud) - Word cloud generation
  - [nltk](https://www.nltk.org/) - Natural language processing
  - [atproto](https://github.com/bluesky-social/atproto) - Bluesky API interaction
