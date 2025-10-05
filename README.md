# yt-playlist-url-getter
Pulls and echos a list of URL's from a Youtube Playlist using yt-dlp

## Dependencies: 
`yt-dlp` or `jq`
- Windows/Python: `pip install -U yt-dlp`
- Debian/Ubuntu: `sudo apt install jq`
- Arch: `packman -S install yt-dlp`
- Fedora: `dnf install yt-dlp`
- MacOS: `brew install jq`

## Script
`list_youtube_playlist_videos.sh`

## Usage
`./list_youtube_playlist_videos.sh "https://www.youtube.com/playlist?list=YOUR_LIST_ID"`

## Output
```
https://www.youtube.com/watch?v=xxxxxxx
https://www.youtube.com/watch?v=yyyyyyy
...
```

## Make executable
`chmod +x list_youtube_playlist_videos`
