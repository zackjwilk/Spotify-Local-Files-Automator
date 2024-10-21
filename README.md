### Spotify Local Files Automator
---
Spotify Local Files Automator is a Python script that takes user input of a song title and artist name and/or link to song on SoundCloud and rips the song from SoundCloud, downloads it, adds metadata (title, artist, cover image), and places it in the user's specified Spotify local files folder so they can listen to it on Spotify.

SoundCloud got rid of its API allowing downloads of songs, so the program listens for responses containing "mp3", downloads these splices of the songs, and pieces them together to combat this.

### Installation
---
Clone the repository:

`git clone https://github.com/zackjwilk/spotify-local-files-automator.git`

### Usage
---
Install dependencies with pip:

`pip install -r requirements.txt`

Set songs folder to your local files folder on Spotify and run local_files_automator.py!
