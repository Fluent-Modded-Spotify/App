### Project Overview

This filter list was created 2015 and is under MIT license by CHEF-KOCH, it contains all the advertising domains which are hard-coded within Spotify (free account).

The project is unofficial and not in any relationship with [Spotify AB](https://web.archive.org/web/20200722142121/https://en.wikipedia.org/wiki/Spotify). Spotify (C) is a trademark of Spotify AB. An unofficial [FAQ can be found here](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free/blob/master/Spotify FAQ.md), read it - it's worth it!.

~~# Project is closed and merged within [CK's-FilterList](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/CKs-FilterList) ([mirror](https://web.archive.org/web/20200722142121/https://gitlab.com/CHEF-KOCH/cks-filterlist))!~~

[![HitCount](https://web.archive.org/web/20200722142121im_/https://camo.githubusercontent.com/2f6e28680d10a5638f28ea913b14a2aeb05df5f0/687474703a2f2f686974732e6477796c2e696f2f434845462d4b4f43482f53706f746966792d41642d667265652e737667)](https://web.archive.org/web/20200722142121/http://hits.dwyl.io/CHEF-KOCH/Spotify-Ad-free) [![GitHub release](https://web.archive.org/web/20200722142121im_/https://camo.githubusercontent.com/5f8a6133608119b912963a4528cf56a3603f46fe/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f434845462d4b4f43482f53706f746966792d41642d667265652e7376673f6c6162656c3d4c617465737425323052656c65617365267374796c653d706f706f7574)](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free/releases/latest) [![Twitter URL](https://web.archive.org/web/20200722142121im_/https://camo.githubusercontent.com/ddf7743d7586e539758b55536870a8f33ff0d408/68747470733a2f2f696d672e736869656c64732e696f2f747769747465722f75726c2f68747470732f747769747465722e636f6d2f666f6c645f6c6566742e7376673f7374796c653d736f6369616c266c6162656c3d466f6c6c6f77253230253430434845462d4b4f4348)](https://web.archive.org/web/20200722142121/https://twitter.com/CKsTechNews) [![Discord](https://web.archive.org/web/20200722142121im_/https://camo.githubusercontent.com/78f82464f21419ab43eeeda11c2bbeec70f364a8/68747470733a2f2f646973636f72646170702e636f6d2f6170692f6775696c64732f3431383235363431353837343837353430322f7769646765742e706e67)](https://web.archive.org/web/20200722142121/https://discord.me/CHEF-KOCH)

## Table of Contents

- Table of Contents
  - [How to Debug problems?](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#how-to-debug-problems)
  - [Spotify (app) privacy](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#spotify-app-privacy)
  - [Release & RePack information](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#release--repack-information)
- [Spotify Recorder](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#spotify-recorder)
- [Spotify Backup Projects](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#spotify-backup-projects)
- [Spotify Windows Ad-Blocker Projects](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#spotify-windows-ad-blocker-projects)
- [Spotify Browser Extensions](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#spotify-browser-extensions)
- [Android](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#android)
- MacOS
  - [Ad-Block Browser extension (for Spotify Web)](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#ad-block-browser-extension-for-spotify-web)
  - [Spotify Review of the year](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#spotify-review-of-the-year)
  - [Spotify Downloader (CLI)](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#spotify-downloader-cli)
  - [Criticism of Spotify](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#criticism-of-spotify)
  - [Analyze Spotify GDPR data streams](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#analyze-spotify-gdpr-data-streams)
  - [Spotify Service Alternatives](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#spotify-service-alternatives)
  - [Spotify Equalizer](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#spotify-equalizer)
  - [Reference](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#reference)
  - [Reversing Spotify](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free#reversing-spotify)

### How to Debug problems?

Spotify comes with a hidden debug console. You can start Spotify via `spotify --show-console` command line parameter in order to start/reveal the console window.

### Spotify (app) privacy

You can easily import the "blocker" (filters) list into any Ad-blocker or download the pre-made Ad-Free versions. A HOSTS file is not a "crack" and not something you get banned for while using it.

An additional advice is to set the following parameters within the Spotify app:

- Edit - Preferences (CTRL + P) - Privacy *Block all cookies...* (enable it)
- Edit - Preferences (CTRL + P) - Advertisement - Change advertising preferences (disable everything here on the Spotify website)
- Manually delete the Spotify cache folder and mark it as _read-only_so that Spotify won't get access tp it, which prevents to store meta-data and ads in it.

This helps to get rid of [cookie leftover(s) tracker(s)](https://web.archive.org/web/20200722142121/https://old.reddit.com/r/privacy/comments/eqzg51/what_about_the_privacy_of_my_data_in_spotify/) and reduces the chance to see banner ads (it does not remove them!).

### Release & RePack information

I do *not officially maintain this project* which means every work I still do is for the community only and entirely for free. I spent a lot of time debugging and inspecting Spotify's traffic.

No one is forced to download something from the [release tab](https://web.archive.org/web/20200722142121/https://github.com/CHEF-KOCH/Spotify-Ad-free/releases) nor do I support something illegal here. Repacking the installer is not illegal, however modifying the files itself is because it's against ToS (which I respect) but including several additional patches and a HOSTS file seems pretty much okay because Spotify does include already anti-blocking debugging techniques to prevent all of this. Abusing "holes" is illegal.

In this repo I provide:

- Ad-Free mods for Desktops and the Android OS. MacOS is official not supported because I don't use any Apple products.
- Filter lists in order to block ads (via hosts).

## Spotify Recorder

- [Spytify](https://web.archive.org/web/20200722142121/https://github.com/jwallet/spy-spotify) - Records Spotify without ads while it plays and includes media tags to the recorded files
- [Recording audio playing on the computer via audacity](https://web.archive.org/web/20200722142121/https://manual.audacityteam.org/man/tutorial_recording_audio_playing_on_the_computer.html)
- [spotify-ripper](https://web.archive.org/web/20200722142121/https://github.com/hbashton/spotify-ripper)
- [Sidify](https://web.archive.org/web/20200722142121/https://www.sidify.de/)

## Spotify Backup Projects

- [SpotMyBackup](https://web.archive.org/web/20200722142121/https://github.com/secuvera/SpotMyBackup) - Backup your playlist & tracks!

## Spotify Windows Ad-Blocker Projects

- [BlockTheSpot](https://web.archive.org/web/20200722142121/https://github.com/mrpond/BlockTheSpot/releases) - Spotify injection (for the Windows Desktop version only) which blocks video, audio & banner

## Spotify Browser Extensions

- [Lyrics With Spotify Web Player](https://web.archive.org/web/20200722142121/https://github.com/mantou132/Spotify-Lyrics) - [Chrome](https://web.archive.org/web/20200722142121/https://chrome.google.com/webstore/detail/spotify-lyrics/mkjfooclbdgjdclepjeepbmmjaclipod) | [Firefox](https://web.archive.org/web/20200722142121/https://addons.mozilla.org/en-US/firefox/addon/spotify-lyrics/)

## Android

- [abertschi/ad-free](https://web.archive.org/web/20200722142121/http://adfree.abertschi.ch/) - A modularized Ad Blocker for Spotify on Android.

## Linux

- [spotify-adblock-linux](https://web.archive.org/web/20200722142121/https://github.com/abba23/spotify-adblock-linux/)

## MacOS

- [spotify-adblock-macos](https://web.archive.org/web/20200722142121/https://github.com/AnanthVivekanand/spotify-adblock-macos)
- ~~[MuteSpotifyAds](https://web.archive.org/web/20200722142121/https://github.com/simonmeusel/MuteSpotifyAds) - A efficient MacOS application automatically silencing ads on the Spotify desktop app.~~
- ~~[librespot](https://web.archive.org/web/20200722142121/https://github.com/plietar/librespot)~~
- [Macsome Spotify Downloader](https://web.archive.org/web/20200722142121/https://www.macsome.com/spotify-downloader/) Paid Spotify Music Downloader.

### Ad-Block Browser extension (for Spotify Web)

- [Spotify "crack" Chrome App](https://web.archive.org/web/20200722142121/https://github.com/sooxiaotong/spotify-crack-chrome-app) - Basically an app for Chrome in case you never heard of uBlock, AdGuard & Co.

### Spotify Review of the year

- [Review of the year (2019) - Needs Spotify login](https://web.archive.org/web/20200722142121/https://www.spotify.com/en/wrapped/)

### Spotify Downloader (CLI)

- [Chimera](https://web.archive.org/web/20200722142121/https://notabug.org/Aesir/chimera) - Multi music downloader for deezer, tidal, qobuz, soundcloud, napster, gpm, dtq & Spotify.
- [Spicetify-cli](https://web.archive.org/web/20200722142121/https://github.com/khanhas/spicetify-cli) - Commandline tool to customize Spotify client.
- [Spotify Downloader Utility](https://web.archive.org/web/20200722142121/https://github.com/SwapnilSoni1999/spotify-dl) - Download playlist and songs from Spotify URL.
- [Spotify Downloader](https://web.archive.org/web/20200722142121/https://github.com/ritiek/spotify-downloader) - Download Spotify playlists with album art and meta-tags.
- [XSpotify](https://web.archive.org/web/20200722142121/https://github.com/maxarmin/XSpotify-1) - A modified Spotify client with DRM bypass (*160 kb/s, 32-bit, 44100 Hz, .ogg format*)

### Criticism of Spotify

- The spotify clients aren't open source
- [Spotify now requiring users to share location data to prevent abuse of family plan](https://web.archive.org/web/20200722142121/https://9to5mac.com/2019/09/12/spottily-family-plan-location/)
- other [stuff mentioned on Wikipedia](https://web.archive.org/web/20200722142121/https://en.wikipedia.org/wiki/Criticism_of_Spotify)
- [Proof that Spotify collects everything](https://web.archive.org/web/20200722142121/https://twitter.com/steipete/status/1025024813889478656) + they [sell your private data](https://web.archive.org/web/20200722142121/https://betanews.com/2016/07/22/spotify-sells-user-data-to-advertisers/)
- [Yay for Bloatware: Samsung to Pre-Install Spotify on Its Smartphones](https://web.archive.org/web/20200722142121/https://news.softpedia.com/news/yay-for-bloatware-samsung-to-pre-install-spotify-on-its-smartphones-525250.shtml)

### Analyze Spotify GDPR data streams

- [SpotifyStats source code](https://web.archive.org/web/20200722142121/https://github.com/Maxr1998/SpotifyStats) & [Analyzer webpage](https://web.archive.org/web/20200722142121/https://maxr1998.github.io/SpotifyStats/)

### Spotify Service Alternatives

- [Amazon Prime Music](https://web.archive.org/web/20200722142121/https://www.amazon.com/Amazon-Music/)
- [Apple Music](https://web.archive.org/web/20200722142121/https://www.apple.com/chde/music/)
- [Audius](https://web.archive.org/web/20200722142121/https://audius.co/)
- [Bandcamp](https://web.archive.org/web/20200722142121/https://bandcamp.com/)
- [BandCamp](https://web.archive.org/web/20200722142121/https://bandcamp.com/)
- [Deezer](https://web.archive.org/web/20200722142121/https://www.deezer.com/en/)
- [gramophy](https://web.archive.org/web/20200722142121/https://github.com/ladiesman6969/Gramophy)
- [Last.fm](https://web.archive.org/web/20200722142121/http://www.last.fm/)
- [Mflow](https://web.archive.org/web/20200722142121/http://beta.mflow.com/)
- [Murfie](https://web.archive.org/web/20200722142121/https://www.murfie.com/)
- [Musicovery](https://web.archive.org/web/20200722142121/http://b2b.musicovery.com/)
- [MusicUp](https://web.archive.org/web/20200722142121/https://getmusicup.com/)
- [nuclear](https://web.archive.org/web/20200722142121/https://github.com/nukeop/nuclear) - A free alternative to Spotify. No DRM. 100% free software. Pulls music from Youtube, Soundcloud and Bandcamp.
- [Pandora Radio](https://web.archive.org/web/20200722142121/https://www.pandora.com/)
- [Qobuz](https://web.archive.org/web/20200722142121/https://www.qobuz.com/gb-en/discover)
- [Radioplayer](https://web.archive.org/web/20200722142121/https://www.radioplayer.co.uk/)
- [Roon](https://web.archive.org/web/20200722142121/https://roonlabs.com/)
- [Saavn](https://web.archive.org/web/20200722142121/https://www.jiosaavn.com/)
- [Slacker Radio](https://web.archive.org/web/20200722142121/https://www.livexlive.com/)
- [SoundCloud](https://web.archive.org/web/20200722142121/https://soundcloud.com/)
- [Stereomood](https://web.archive.org/web/20200722142121/https://stereomood.com/)
- [Subsonic](https://web.archive.org/web/20200722142121/http://www.subsonic.org/pages/index.jsp)
- [Tidal](https://web.archive.org/web/20200722142121/https://tidal.com/)
- [YouTube Music](https://web.archive.org/web/20200722142121/https://music.youtube.com/) / [YouTube Vanced](https://web.archive.org/web/20200722142121/https://vanced.app/)

### Spotify Equalizer

- Spotify seems to work on an integrated Equalizer (for the Web Player) | [Source](https://web.archive.org/web/20200722142121/https://twitter.com/wongmjane/status/1226825288119537664?ref_src=twsrc^tfw)

### Spotify Video

- Spotify prepares video integration | [Source](https://web.archive.org/web/20200722142121/https://twitter.com/wongmjane/status/1274452040358346752)

### Reference

- [Spotify Terms and Conditions of Use](https://web.archive.org/web/20200722142121/https://www.spotify.com/us/legal/end-user-agreement/#s9)
- [How Good Is Spotify's Audio Quality?](https://web.archive.org/web/20200722142121/https://www.xaprb.com/blog/spotify-audio-quality/)
- [Spotify API documentation](https://web.archive.org/web/20200722142121/https://developer.spotify.com/documentation/web-api/)

### Reversing Spotify Client

- [Reversing the MacOS Spotify Client](https://web.archive.org/web/20200722142121/https://medium.com/@lerner98/skiptracing-reversing-spotify-app-3a6df367287d)
- [Spotify vs OllyDbg](https://web.archive.org/web/20200722142121/http://www.steike.com/code/spotify-vs-ollydbg/)
- [Breaking Spotify DRM with PANDA](https://web.archive.org/web/20200722142121/http://moyix.blogspot.com/2014/07/breaking-spotify-drm-with-panda.html)
- [Reverse engineering Spotify and Chromecast protocols to let my vocal assistant play music](https://web.archive.org/web/20200722142121/https://developers.caffeina.com/reverse-engineering-spotify-and-chromecast-protocols-to-let-my-vocal-assistant-play-music-ada4767efa2?source=linkShare-7c6a9af31a39-1517909746)
- [Automatic Hooking/Patching for Spotify on MacOS](https://web.archive.org/web/20200722142121/https://medium.com/swlh/skiptracing-automated-hook-resolution-74eda756533d)