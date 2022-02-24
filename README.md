# Magic ML Mixer: Make Mixes from your Top Spotify Listens using sklearn KMeans

If you're like me and just dump all songs into the standard *"Liked Songs"* i.e don't have the patience to maintain different playlists - then this is for you.

Let DJ Python 🎧 with some magic ML, cluster your Liked Songs into mixes 🪄

## What is covered in the `MLMagicMixer.ipynb`:

1. Authenticating a Spotipy Client instance with our creds, to fetch our Top Listens.
2. Get Audio Features for each of the fetched Tracks, and see how the features change/correlate across our Tracks
3. Perform `KMeans clustering` to make new Mix(s)!
4. Finally, add these new Mix(s) to our Spotify account 🚀

## Spotify Developers Creds for the API

* Go to https://developer.spotify.com/dashboard/ and click ```Create a Client ID``` or ```Create an App``` to get your ``Client ID`` and ``Client Secret``. 
* Edit settings and add ``http://localhost:4444/callback`` in the ``Redirect URI`` field.


## Code Setup

* After cloning this repo, ```cd``` into it.
* Run ```pip install -r requirements.txt```
* Run ```jupyter notebook```, if you have it installed. Installation instructions: [here](https://jupyter.org/install)
* Open ```MagicMLMixer``` in your browser 
* Switch in your ``Client ID`` and ``Client Secret`` wherever indicated.
* Stay tuned for the Show & Tell ✨

