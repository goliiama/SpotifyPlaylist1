# Spotify Credential Access
To access your Spotify credentials securely, set the following environment variables:
- `SPOTIFY_CLIENT_ID`: Your Spotify Client ID
- `SPOTIFY_CLIENT_SECRET`: Your Spotify Client Secret

# Scraping Billboard 100
To retrieve Billboard Hot 100 songs for a specific date, follow these steps:

1. Run the script and provide the desired year in the format YYYY-MM-DD when prompted.
2. The script will then scrape the Billboard Hot 100 chart for the given date.

# Spotify Authentication
To enable Spotify integration, ensure you have set up the Spotify Developer credentials in your environment variables as mentioned above. The script will authenticate with Spotify using these credentials.

# Searching Spotify for Songs
The script will search Spotify for each song from the Billboard Hot 100 chart for the specified year. It will attempt to match the songs and create a list of their Spotify URIs. Any songs not found in Spotify will be skipped and reported.

# Creating a New Private Playlist in Spotify
After retrieving the song URIs, the script will create a new private Spotify playlist named after the specified date and containing the Billboard Hot 100 songs for that year.

# Adding Songs to the New Playlist
Finally, the script will add the songs found on Spotify to the newly created private playlist.

Ensure that your environment variables are correctly set, and you have the necessary permissions to perform these operations on your Spotify account.

