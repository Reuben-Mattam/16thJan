# Stats.Sptfy
Spotify Stats Tracker 


all files in master,
trackersptfy.py is for spotify tracking, creating an excel file of all your saved stats. it requires you to set up a .env file with the following format:


SPOTIFY_CLIENT_ID=
SPOTIFY_CLIENT_SECRET=
SPOTIFY_REDIRECT_URI=http://localhost:8888/callback


statssptfy.py is the python code for the app. It takes the output excel file from trackersptfy.py and uses that.
