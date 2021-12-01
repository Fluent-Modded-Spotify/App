<h1 style="text-align:center">

# Fluent-Modded-Spotify

  ![](https://raw.githubusercontent.com/pronoy2108/Fluent-Modded-Spotify/main/spotify-icon.png)
  <p align="center">Icon made by <a href="https://t.me/Qirkl">Qirkl</a></p>
<p align="center">Spotify, but with a hint of Fluent Design</p>

</h1>


### [williamckha/spicetify-fluent](https://github.com/williamckha/spicetify-fluent)

  [Spicetify](https://github.com/khanhas/spicetify-cli) theme inspired by Windows 11 UI and Microsoft's Fluent Design  

</div>

<br>

![dark-1](https://github.com/williamckha/spicetify-fluent/blob/master/screenshots/dark-1.png?raw=true)  
<br>
![dark-2](https://github.com/williamckha/spicetify-fluent/blob/master/screenshots/dark-2.png?raw=true)  
<br>
![light-1](https://github.com/williamckha/spicetify-fluent/blob/master/screenshots/light-1.png?raw=true)  
<br>

## About


Requires Segoe UI font.

Based off [Ziro](https://github.com/schnensch0/ziro) theme by [schnensch](https://github.com/schnensch0)  
[Fluent UI System Icons](https://github.com/microsoft/fluentui-system-icons) by Microsoft Corporation  
[Phosphor Icons](https://github.com/phosphor-icons/phosphor-icons) by Phosphor Icons

## Install
Make sure spicetify >= v2.6.6 is installed. Run these commands:

### Windows
In **Powershell**:
```powershell
cd "$(spicetify -c | Split-Path)\Themes"
git clone https://github.com/williamckha/spicetify-fluent Fluent
Copy-Item Fluent\fluent.js ..\Extensions
spicetify config extensions fluent.js
spicetify config current_theme Fluent color_scheme dark
spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
spicetify apply
```

### macOS and Linux
In **Bash**:
```bash
cd "$(dirname "$(spicetify -c)")/Themes"
git clone https://github.com/williamckha/spicetify-fluent Fluent
mkdir -p ../Extensions
cp Fluent/fluent.js ../Extensions/.
spicetify config extensions fluent.js
spicetify config current_theme Fluent color_scheme dark
spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
spicetify apply
```

## Customization
Three color schemes are available: `light`, `dark` or `dracula`. Change scheme with commands:
```
spicetify config color_scheme <scheme_name>
spicetify apply
```
You can change the accent color in the theme folder's color.ini file.  
If you are using Windows, you can hide the window controls by adding the flag `--transparent-window-controls` after Spotify.exe in your Spotify shortcut.

---

### [khanhas/spicetify-cli](https://github.com/khanhas/spicetify-cli)

<h3 align="center"><img src="https://i.imgur.com/iwcLITQ.png" width="600px"></h3>
<p align="center">
  <a href="https://goreportcard.com/report/github.com/khanhas/spicetify-cli"><img src="https://goreportcard.com/badge/github.com/khanhas/spicetify-cli"></a>
  <a href="https://github.com/khanhas/spicetify-cli/releases/latest"><img src="https://img.shields.io/github/release/khanhas/spicetify-cli/all.svg?colorB=97CA00?label=version"></a>
  <a href="https://github.com/khanhas/spicetify-cli/releases"><img src="https://img.shields.io/github/downloads/khanhas/spicetify-cli/total.svg?colorB=97CA00"></a>
  <a href="https://discord.gg/VnevqPp2Rr"><img src="https://img.shields.io/discord/842219447716151306?label=Chat&logo=discord&logoColor=discord"></a>
  <a href="https://www.reddit.com/r/spicetify"><img src="https://img.shields.io/reddit/subreddit-subscribers/spicetify?style=social"></a>
</p>

Command-line tool to customize the official Spotify client.
Supports Windows, MacOS and Linux.

<img src="https://user-images.githubusercontent.com/26436809/118751529-d0abcf00-b8a4-11eb-9876-8b15f930a691.png" alt="img" align="right" width="500px">  

### Features
- Change colors whole UI
- Inject CSS for advanced customization
- Inject Extensions (Javascript script) to extend functionalities, manipulate UI and control player.
- Inject Custom apps
- Remove bloated components to improve performance

#### [Installation](https://github.com/khanhas/spicetify-cli/wiki/Installation)
#### [Basic Usage](https://github.com/khanhas/spicetify-cli/wiki/Basic-Usage)
#### [Customization](https://github.com/khanhas/spicetify-cli/wiki/Customization)
#### [Extensions](https://github.com/khanhas/spicetify-cli/wiki/Extensions)
#### [Custom Apps](https://github.com/khanhas/spicetify-cli/wiki/Custom-Apps)
#### [Wiki](https://github.com/khanhas/spicetify-cli/wiki)

## Installation

#### Windows:

- Download the two files from Releases
- Copy them to a folder in an easily accessible location like Desktop
- Install ```scoop``` using ```iwr -useb get.scoop.sh | iex```
- After scoop is installed, type ```Set-ExecutionPolicy unrestricted``` in Powershell with elevated privileges
- Run Spotify.exe as admin (it's a 7z archive and requires admin to extract the files for some reason)
- Run ```autorunscript.ps1``` to install all dependencies
- Extract it to the same location
- Run ```Fluent Spotify.exe``` 
- Install it however you want, for all users/for the current user only
- After installing, go to the ```Spotify``` folder you just extracted and run ```Spotify.exe```
- You should have Fluent Design in the Spotify app now!

#### Linux:

* Download the two files from Releases
* Run ```autorunscript.sh``` to install all dependencies.
* Run ```Fluent Spotify.deb``` 

<h10>Credits: Installation steps by [donut2008](https://github.com/donut2008)</h10>

Note: ```autorunscript.ps1``` is a file which automatically installs the dependencies for this app (needs admin priviledges to work)
