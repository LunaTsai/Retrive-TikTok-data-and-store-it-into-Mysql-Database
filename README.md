# Retrieve TikTok data and fetch it into Mysql Database

# Overview
This repository contains a Python script designed to retrieve user posts and comments from TikTok using the Ensemble Data API and then store the data in a MySQL database

# Features
1. Data Retrieval:
   - Developed a Python script to interact with the **Ensemble Data API**.
   - Used the **`requests` library** for making efficient HTTP requests and handling API responses.

2. Data Manipulation:
   - Employed **Pandas** for data manipulation.
   - Normalized **JSON data** retrieved from TikTok.
   - **Converted Unix timestamps** to a human-readable format.

3. Database Interaction:
   - Integrated **SQLAlchemy** to facilitate interaction with a MySQL database.
   - Stored the retrieved TikTok data in the MySQL database for future use.

