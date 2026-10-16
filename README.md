# VideoVault

**Download videos and audio straight into Premiere Pro and After Effects.**

VideoVault is a panel for Adobe Premiere Pro / After Effects. Paste a link, pick video
or audio, optionally trim it, and the clip downloads and drops right into your open
project — no sketchy websites, no extra tabs.

This is the **final, free build** of VideoVault. It is self-maintaining: the download
engine (`yt-dlp`) updates itself automatically, so it keeps working without any new
release.

---

## Download

**➡ [Download the latest installer](https://github.com/JiggypuffFridays/VideoVault5/releases/latest/)**

> Windows only. Requires Adobe Premiere Pro or After Effects.

---

## Install

1. Run **VideoVault Installer v5.exe**.
2. Approve the Windows prompt (it installs the panel and, if you had the old VideoVault 3,
   removes it for you — your downloaded files and history are kept and carried over).
3. Open Premiere Pro or After Effects → **Window ▸ Extensions ▸ VideoVault**.

> The installer is not code-signed, so Windows SmartScreen may show a one-time
> "unknown publisher" notice — choose **More info ▸ Run anyway**.

## Use

1. Paste a URL (YouTube, TikTok, Instagram, Facebook, X/Twitter, Reddit, Twitch, …).
2. Choose **Video** (MP4 / H.264) or **Audio** (MP3).
3. *(Optional)* open the ☰ menu for quality (480p–4K), a trim range, browser cookies
   (for age-gated or login-only videos), auto-import, and your save folder.
4. Click **Download** — it saves to your folder and imports into the open project.

## Features

- One-click download into Premiere Pro / After Effects
- Video (MP4/H.264, Premiere-native) or audio (MP3)
- Quality up to 4K
- Trim a clip to a start/end range
- Playlists — pick which videos to grab
- Browser-cookie support for restricted videos
- Download history with re-import / reveal in folder
- **Self-updating** — the engine keeps itself current automatically

## Where files go

By default your system **Downloads** folder (or wherever you last set it). You can change
the save folder, or point it at your current project folder, from the ☰ menu.

---

## Credits

Made by **Jiggy** ([@jiggywastaken](https://www.twitter.com/jiggywastaken)).

Built on the excellent open-source [yt-dlp](https://github.com/yt-dlp/yt-dlp) and
[FFmpeg](https://ffmpeg.org/) projects — see [THIRD-PARTY-NOTICES.md](./THIRD-PARTY-NOTICES.md).

Licensed under the [MIT License](./LICENSE).
