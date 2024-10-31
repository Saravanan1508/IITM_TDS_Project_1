# IITM_TDS_Project_1
Github webscraping

## Project Overview

This project collects and analyzes GitHub user data from Shanghai, specifically focusing on users with more than 200 followers and their repositories. Data fields include user profiles, repository details, programming languages, and repository features.

### Files Included

- **users.csv**: Contains data for each user with fields like login, name, company, location, email, and more.
- **repositories.csv**: Lists repositories for each user with details on repository name, creation date, language, and license information.
- **TDS_Project-1.ipynb**: Python script used to collect and organize the data from GitHub’s API.


# GitHub User and Repository Data Analysis

- Data was scraped from GitHub's API using a Colab notebook to gather information on users in Shanghai with over 200 followers, including up to 500 of their most recent repositories.
- Notably, some data is in Chinese, and many high-follower users contribute to repositories in various languages beyond just JavaScript and Python.
- Initially, it’s best to scrape a small subset of data to ensure the process runs smoothly, saving time by avoiding lengthy re-scrapes with each code adjustment. Developers should be proficient in pandas, shell commands, and Excel to enhance data analysis.
