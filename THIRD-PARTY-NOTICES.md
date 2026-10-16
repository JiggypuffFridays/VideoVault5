# Third-party notices

VideoVault relies on two open-source projects.

## yt-dlp
- Project: https://github.com/yt-dlp/yt-dlp
- License: The Unlicense (public domain)
- Use: VideoVault downloads the latest `yt-dlp` binary at runtime into a per-user folder
  (`%APPDATA%\VideoVault\bin`) and keeps it updated. It is **not** bundled in the
  installer.

## FFmpeg
- Project: https://ffmpeg.org/
- License: FFmpeg is free software licensed under the GNU LGPL or GPL depending on how it
  was built. The `ffmpeg.exe` / `ffprobe.exe` binaries shipped with this installer are a
  standard Windows build obtained from a public FFmpeg distribution.
- License text: https://www.gnu.org/licenses/ and https://ffmpeg.org/legal.html
- Use: VideoVault calls FFmpeg to merge video+audio and to extract/convert audio.

> If you redistribute the FFmpeg binaries, follow the terms of the applicable FFmpeg
> license (for a GPL build, that includes making the corresponding source available).
> The FFmpeg source for these builds is published by the distributor linked above.

All other product names, logos, and brands are property of their respective owners.
