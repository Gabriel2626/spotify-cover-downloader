![logo](https://i.imgur.com/R7G5mwz.png)

### Download album covers from Spotify!

*Note: Before using this script, you'll need to create an app at [Spotify’s developer site](https://developer.spotify.com/web-api/) and get a `client_id` and `client_secret`.*

#### Requirements
- python2+
- virtualenv

```
> virtualenv env
> source ./env/bin/activate
> pip install requirements.txt
```

#### Usage

```
python spotify_cover_downloader.py --client_id xxxx --client_secret xxxx --directory ~/Downloads spotify:track:1kGb78PHGlylL7s9Nw79Si
```

> This scripts supports song links and Spotify URI (https://open.spotify.com/intl-pt/track/2kJIRtytgFsVFoM5lDSYVN)

> You can also hardcode your `client_id` and `client_secret` if you don't want to pass it as a parameter
