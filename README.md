Spotify Track Data Extractor & Analyzer
This project automates the extraction of music metadata from Spotify URLs using the Spotify Web API. It processes track information, stores it in a MySQL database, and provides data visualization and analysis capabilities.

## 🚀 Features
URL Parsing: Uses Regex to extract unique track IDs from Spotify links.

Metadata Extraction: Retrieves track name, artist, album, popularity, and duration.

Batch Processing: Reads multiple URLs from a track_urls.txt file for bulk processing.

Database Management: Stores data in a structured MySQL table for long-term storage and querying.

Data Visualization: Uses Matplotlib to create visual reports of track popularity and metrics.

## 🛠 Tech Stack
Language: Python 3.x

API: Spotipy (Spotify Web API wrapper)

Database: MySQL

Libraries: Pandas, Matplotlib, mysql-connector-python, Re.
