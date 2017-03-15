# singlespotify 🎵

> Create Spotify playlists based on one artist through the command line

![](https://img.shields.io/badge/node-7.7.1-brightgreen.svg)

![](singlespotify1.gif)

<!--- 
[![asciicast](https://asciinema.org/a/4k49ag6gy3bknaa6ryoubhcy5.png)](https://asciinema.org/a/4k49ag6gy3bknaa6ryoubhcy5)
-->

## Install
`$ npm install -g singlespotify` <br><br>
**Note:** Node version 7.7.1+ required. `$ node -v` to check which version you have installed. The latest version can be downloaded [here](https://nodejs.org/en/)

## Usage
`$ singlespotify --artist [-a] "artist_name"`

The program will then prompt you for your Spotify username and bearer token. <br><br>

You can get the bearer token here: https://developer.spotify.com/web-api/console/post-playlists/ <br>
Click **GET OAUTH TOKEN** and make sure to check *playlist-modify-public* 

`$ singlespotify --help`

```
    Usage
      $ singlespotify --artist [-a] "artist_name" --config [-c] /path/to/config.json

    Example
      $ singlespotify -a "Kanye West" -c /Users/kabirvirji/config.json

    For more information visit https://github.com/kabirvirji/singlespotify
```

## Changelog
- **03/15/17** Added [Inquirer](https://github.com/SBoudrias/Inquirer.js) and [conf](https://github.com/sindresorhus/conf) for authentication


Shoutout to [kshvmdn](https://github.com/kshvmdn) for all the help!


