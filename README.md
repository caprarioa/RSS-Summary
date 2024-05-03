RSS Feed Summarizer

Project Overview

This Python project automates the fetching and summarizing of articles from a given RSS feed. The application fetches the first 10 articles from the RSS URL and then uses OpenAI's GPT-3.5-turbo model to generate summaries grouped by the geographical region of the countries involved. The summaries are saved to a text file for later use.

Features
Fetches articles from RSS feeds.
Summarizes articles using OpenAI's GPT-3.5-turbo model.
Summaries are grouped by country and region.
Saves summaries to a text file.
Setup and Installation
Clone the repository

`git clone (https://github.com/caprarioa/RSS-Summary)
cd rss-feed-summarizer`

Install required packages
Ensure you have Python installed on your system. Then run:

`pip install -r requirements.txt`

Set up the environment variables
Create a .env file in the project root directory.
Add the following line to the .env file:

`OPENAI_API_KEY='Your-OpenAI-API-Key-Here'`

Usage
Run the script with the following command:

`python main.py`

The script will fetch articles from the specified RSS feed, summarize them, and save the summary to a text file named daily_synopsis.txt.

Configuration
To change the RSS feed URL, modify the rss_url variable in the main() function of the main.py script.

Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

Please ensure to update tests as appropriate.

License
MIT
