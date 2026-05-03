# vlc-yt-dlp

A VLC addon for [yt-dlp](https://github.com/yt-dlp/yt-dlp) integration.

### Prerequisites

- **yt-dlp** installed and available in `$PATH`.
- **Deno** (or Node.js) – a JavaScript runtime required by YouTube to solve bot challenges.
- Firefox (or another supported browser) with an active YouTube login session. The script reads cookies directly from the browser to authenticate your requests.

### Installation

Put [`yt-dlp.lua`](https://github.com/nileric/vlc-youtube/blob/main/yt-dlp.lua) into:

- In Windows: `%APPDATA%\vlc\lua\playlist\`
- In Mac OS X: `/Users/%your_name%/Library/Application Support/org.videolan.vlc/lua/playlist/`
- In Linux: `~/.local/share/vlc/lua/playlist/`

### Usage

Simply open a YouTube link in VLC. You will not be able to seek so if you want to start at a particular time set that in vlc when you are at the "open network stream" window.

### Credits

This is a fork of mjasny's [vlc-youtubeDL](https://github.com/mjasny/vlc-youtubeDL), originally adapted for [yt-dlp by robturner45](https://github.com/robturner45/vlc-yt-dlp). Further modifications were made to support YouTube authentication and JavaScript challenges.
