Features
API Integration: Connects to Spotify using Spotipy and OAuth 2.0.

Data Extraction: Fetches user playlists, top tracks, and audio features (danceability, energy, etc.).

Data Processing: Cleans and organizes raw JSON data into structured formats using Pandas.

Visualization: Generates insights into music tastes using Matplotlib or Seaborn.

## Tech Stack
Language: Python

Libraries: spotipy, pandas, matplotlib

Database: SQLite (for caching track data)

Environment: Flask (optional for web-based dashboard)

## Setup Instructions
Clone the Repository:

Bash
git clone https://github.com/shankar516/spotify_test.git
cd spotify_test
Install Dependencies:

Bash
pip install -r requirements.txt
API Credentials:
Create a .env file and add your Spotify Developer credentials:

Code snippet
SPOTIPY_CLIENT_ID='your_client_id'
SPOTIPY_CLIENT_SECRET='your_client_secret'
SPOTIPY_REDIRECT_URI='http://localhost:8080'
