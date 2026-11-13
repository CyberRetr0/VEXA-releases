<p align="center">
  <img src="screens/logo.svg" width="96" alt="VEXA logo">
</p>

<h1 align="center">VEXA</h1>

<p align="center">
  <b>One launcher for every game on your PC.</b><br>
  Steam, Epic, Xbox, Ubisoft, GOG, repacks and plain folders, in one fast library.
</p>

<p align="center">
  <a href="https://github.com/CyberRetr0/VEXA-releases/releases/latest">
    <img src="https://img.shields.io/badge/Download-VEXA%20for%20Windows-7c3aed?style=for-the-badge&logo=windows&logoColor=white" alt="Download VEXA for Windows">
  </a>
</p>

<p align="center">
  <a href="https://github.com/CyberRetr0/VEXA-releases/releases/latest"><img src="https://img.shields.io/github/v/release/CyberRetr0/VEXA-releases?label=latest&color=c084fc" alt="Latest version"></a>
  <a href="https://github.com/CyberRetr0/VEXA-releases/releases"><img src="https://img.shields.io/github/downloads/CyberRetr0/VEXA-releases/total?color=7c3aed" alt="Downloads"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078d4" alt="Windows 10 and 11">
</p>

![Library](screens/library.jpg)

## Features

- **One library:** finds your games from every store and folder, with covers, logos, descriptions and playtime.
- **Big screen mode:** a TV and controller interface with themes, layouts and sounds (F11 or the controller's View button).
- **Discover:** new releases and repacks from several sources, crack status, a wishlist, and a download button on every card.
- **Downloads:** direct links, torrents and magnets in the app, with queue, speed limit, resume and a VPN kill switch.
- **Installers and updates:** an install queue for setup files and archives, plus official patch notes for your games.
- **FPS overlay, storage view, play stats, save backups,** and a command bar on Ctrl+K.
- **Light on your PC:** closed to the tray it rests at about 100 MB of RAM and almost no CPU, so it stays out of your games' way.

<table>
  <tr>
    <td><img src="screens/game.jpg" alt="Game page"></td>
    <td><img src="screens/big.jpg" alt="Big screen mode"></td>
  </tr>
  <tr>
    <td align="center">Game page</td>
    <td align="center">Big screen mode</td>
  </tr>
</table>

![Discover](screens/discover.jpg)

## Lightweight

Measured on Windows 11 (Intel i5-14600K, RTX 5080, 64 games in the library), VEXA plus its web view:

| | RAM in use | CPU (whole PC) |
|---|---|---|
| **Min:** closed to the tray, even right after heavy use | about 108 MB | 0.01% on average |
| **Max:** heavy use: trailers playing, Discover, game pages, Big Picture animations | 1.0 GB at the peak (770 MB on average) | 9.7% at the peak (5% on average) |

When you close the window, VEXA pauses its page and hands its memory back to Windows. In the background it only keeps the tray icon, playtime tracking and a light hourly refresh of your download sources.

## Download and install

1. Download **VEXA-Setup-&lt;version&gt;.exe** from the [latest release](https://github.com/CyberRetr0/VEXA-releases/releases/latest).
2. Run it. It installs for your Windows user only and needs no admin rights.
3. VEXA updates itself: it checks for a new version every time it starts. You can turn automatic updates off in **Settings → About**.

## Safety

- Every update is signed. VEXA refuses any update whose signature does not match the key built into the app.
- Updates download only over HTTPS from this page.
- No accounts and no telemetry.
- VEXA contacts Steam, Wikipedia, PCGamingWiki, iTunes and SteamGridDB for art, descriptions, music and patch notes. Discover reads the public pages of the sources it lists. Downloads start only when you click.
- Anything VEXA deletes goes to the Recycle Bin. Keys you enter (SteamGridDB, debrid) stay on your PC and are never exported.

## Problems or ideas

Open an [issue](https://github.com/CyberRetr0/VEXA-releases/issues), or use **Settings → Report a problem** in the app. It makes a zip of the logs you can attach.

<p align="center"><sub>Made by Phant0m</sub></p>
