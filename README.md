# spotify2mp3
Simple free and unlimited spotify playlist downloads

HOWTO:

- Install the packages required by the application using `pip3 install {package name}`
- Copy the Guest Bearer Token from any Spotify playlist's HTML code.
(If you scroll down on https://open.spotify.com/playlist/1QM1qz09ZzsAPiXphF1l4S, you can find the guest bearer token on line 288 - prettified)
- Enter your playlist ID at the bottom of the script
- Run the script using `python3 run.py`

How does it work?

- We first search the playlist and download a list of songs
- We then look up each song on Youtube, download it as an mp4, then convert it to an mp3 and store it in a folder!
