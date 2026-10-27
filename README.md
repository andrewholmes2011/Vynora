# Vynora

**Your sound. Your universe.**

Vynora is a custom music-player prototype with an original purple-and-gold interface, randomized discovery, search, genre browsing, likes, shuffle/repeat, and a playback bar.

## Included music catalog

Vynora loads a randomized catalog of up to 203 original instrumental tracks from [Keynata Commons](https://carf-coder.github.io/keynata-commons/). The catalog describes its generated tracks as dedicated to the public domain under **CC0 1.0**. Vynora fetches the catalog index and streams MP3s from the source host; it does not copy those audio files into this repository.

The music is primarily generated instrumental material (classical-style pieces, rock-style tracks, J-pop-style pieces, and karaoke arrangements), not a catalog of mainstream commercial recordings. The external catalog must be reachable for these tracks to load. [License information](https://creativecommons.org/publicdomain/zero/1.0/).

## Run it

1. Open the site through GitHub Pages or another web server. Opening the HTML directly from a local file may prevent the remote catalog from loading in some browsers.
2. Wait for the online catalog to load.
3. Select a track to play it. Use the bottom player to pause, skip, seek, adjust volume, shuffle, repeat, or like a track.
4. Use **Import music** to play audio files you own or are licensed to use. Local imports are temporary and stay in the current browser session.

## Current limitations

- The online catalog is randomized for each visit and streams from Keynata Commons, rather than being copied into Vynora's own storage.
- Local imported files are not uploaded or shared and disappear when the page session ends.
- There is no account system, persistent playlists, cloud upload backend, or native phone/TV app in this prototype.
- Vynora is an independent project and is not affiliated with Spotify or Keynata Commons.

## Next development steps

1. Add editable metadata and persistent likes/playlists.
2. Build a secure backend for accounts and listening history.
3. If needed, arrange permitted audio hosting with license/attribution metadata preserved.
4. Add installable PWA support, then consider dedicated mobile and TV apps.

Only upload and distribute music you own or have permission to use.
