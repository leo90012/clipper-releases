# Clipper releases

Installers and updates for **Clipper**, a Windows desktop app for cutting videos into short
clips, adding subtitles, and posting them to YouTube, TikTok, Instagram and X through each
platform's official API.

This repository holds only the release files. Installed copies of Clipper check it for new
versions.

## Install

1. Open the [latest release](../../releases/latest).
2. Download `Clipper_<version>_x64-setup.exe` and run it. It installs for your Windows user
   only and needs no admin rights.
3. Clipper isn't code-signed, so Windows may say "Windows protected your PC". Click
   **More info**, then **Run anyway**.

The `.msi` installs for every user on the PC and needs admin rights. The `.sig` files and
`latest.json` are for Clipper's updater.

Requirements: Windows 10 or 11, 64-bit.

## Updates

Clipper checks this page when it starts and every 6 hours (you can turn that off in
Settings → Updates). New versions download in the background and install only when you
choose **Restart to update**. Each update is checked against Clipper's signing key before it
installs.

## Third-party software

Clipper includes yt-dlp (Unlicense), FFmpeg (GPL v3, built by
[BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds)), and Deno (MIT). Each release's
notes name the exact FFmpeg version with a link to its source code. The full list is in
`licenses\THIRD-PARTY-NOTICES.txt` in the install folder.

Only download and repost content you have the rights to.
