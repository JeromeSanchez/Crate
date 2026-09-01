# Crate

Turn a Spotify playlist into ready-to-click search links on Beatport, Traxsource, Bandcamp and Qobuz — so buying WAV/FLAC files for DJing is a few clicks instead of a manual search per track.

**Live:** _add your GitHub Pages URL here once deployed (Settings → Pages)_

## What it does

- Paste a tracklist (or upload a CSV) — it parses out title and artist for every track
- Generates a search link on each store, plus a "Search all stores" link that queries all four at once
- Per-track status — Pending / Found / Purchased / Skip — saved automatically as you work
- Export the list back out as CSV
- Add your own store with a custom search URL template (`+ Add store`)

## Getting a tracklist out of Spotify

Open the playlist, select all tracks (Ctrl/Cmd+A), copy (Ctrl/Cmd+C), and paste into the tool — Spotify copies title and artist automatically, no login needed.

If that's awkward on your setup, [chosic.com/spotify-playlist-exporter](https://www.chosic.com/spotify-playlist-exporter/) or [spotlistr.com](https://www.spotlistr.com/convert/spotify-to-export) turn a playlist link into a CSV you can upload instead.

## A note on formats

Beatport and Traxsource sell WAV/AIFF, not FLAC. Bandcamp and Qobuz are the ones to check if you specifically want FLAC.

## Running it locally

Single static file, no build step, no dependencies. Open `index.html` directly in a browser, or serve the folder with anything that serves static files, e.g. `python3 -m http.server`.

## License

MIT — see [LICENSE](LICENSE).
