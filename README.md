# Intro-to-Spotify-API

This repository is intended to be a guide to connect to a
 users spotify account through Spotify's API spotipy. 
 This API allows a user with a premium account to do 
 pretty much anything like searching albums, creating 
 playlists, modifying playlists and much more. I hope to add 
 tutorials for all these features.
 
 ## Installation
 
 Use the package manager [pip](https://pip.pypa.io/en/stable/) to install spotipy.
 ```
pip install foobar
``` 

## Getting Started

You first need to head over to [Spotify for Developers](https://developer.spotify.com/) and navigate to the dashboard. From there, log into your spotify account
if you haven't already done so, and click **Create An App.**

![](app.gif)
 
Follow the instructions and you should get to a screen that has your client id and client secret. After this there's just a couple more steps.
Click on Edit Settings and under **Redirect URIs** add http://localhost/.

![](redirect.gif)

Now you're going to need these values to connect to your account. Now go check out the quickstart jupyter notebook to get started.
