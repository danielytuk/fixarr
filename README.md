<h1 align="center"> 🛠️ FIXARR  </h1>

<h4 align="center"> Movie & Tv Renamer With Backup Media Server (Plex / Emby / Jellyfin)</h4>

<p style="text-align:center;" align="center">
  <img align="center" src="https://cdn.staticaly.com/gh/sachinsenal0x64/picx-images-hosting@master/fixarr.52f9qd1anpg0.png" width="512px" height="512px"/>
</p>

# 🛠️ FIXARR

![FIXARR)](https://cdn.staticaly.com/gh/sachinsenal0x64/picx-images-hosting@master/fixarr-gui.18d3p8akdsg0.png)

<br>

## 🚀 Features

- 🎬 MOVIE RENAMER
- 📺 TV RENAMER
- 🔺 PLEX BACKUP
- ⚡️ MULTI THREADING
- ♻ PURG UNNECESSARY FILES (NFO,SRT)
- 🐟 JELLYFIN BACKUP (⭕ in progress)
- ❄ EMBY BACKUP (⭕ in progress)
- ⏬ MOVIE & TV SEACHER (⭕ in progress)

<br>

## 💡 Pros

- 🍕 Accurate Results (Even Torrent Movies Can Rename Without Any Issue)
- 🆓 Fully Free And Open Source
- 🧰 All in One Place
- 🧾 Easy to Use

<br>

## 👎 Cons

- 🐌 Slowly Develop

<br>

## 🏮 NOTE

## 🚀 Some Features are Still in Development :)


<br>


## 🆕 BETA CHANNEL

[BETA](https://github.com/sachinsenal0x64/FIXARR)


<br>

# 📐 INSTALLATION

<br>


### 🏮 YOU DONT WANT TO COMPILE FROM SOURCE CODE ITS OPTIONAL. YOU CAN GET PREBUILD INSTALLER FROM [RELEASES](https://github.com/sachinsenal0x64/FIXARR/releases)



<br>

## 🗝 .ENV SETUP (Important):

<br>

- Rename **.env.example** to **.env**
  
- You can get key from [THE MOVIE DB](https://www.themoviedb.org/settings/api?language=en-US) and its totally free.

```
TMDB_API_KEY=tmdbkey
```

<br>

🐧For Linux :

```Terminal

🐧 Ubuntu or Any Other Debian Based Distro :

sudo apt-get install software-properties-common
sudo apt-get install python3.10
sudo apt-get install python3-tk

pip3 install -r requirements.txt
python3 fixarr.py

🐧 Fedora:

sudo dnf install python3
sudo dnf install python3-tkinter

pip3 install -r requirements.txt
python3 fixarr.py

```

<br>

🍎 For macOS :

```Terminal

For Mac OS With BREW:

if you already not install brew then install its from offical site : https://brew.sh/#install 

brew install python3
brew install python-tk@3.10
pip3 install -r requirements.txt
python3 fixarr.py

or just run .bat File also you can create bat_shortcut
```

<br>

🚪 For Windows:

```CMD
First Install Python  

pip install -r requirements.txt
python fixarr.py
```

<br>

## 🏮 NOTE

<br>

IF YOU WANT TO MAKE OWN STANDALONE EXE USE NUITKA TO COMPILE SOURCE CODE INTO C AFTER ITS CAN RUN AS EXE.

<br>

```compile

[Install C Compiler  (http://www.codeblocks.org/downloads/binaries/) and download (including compiler) setup & to work with this setup GCC env path (C:\Program Files\CodeBlocks\MinGW\bin) in your OS SYSTEM ENV ] 

open your cmd in Fixarr PATH

pip -v install nuitka 

nuitka --mingw64 --standalone --windows-icon-from-ico=./assets/i.ico --include-data-dir=./assets=./assets --windows-company-name=FIXARR --product-name=FIXARR --product-version=0.1.0  --file-version=0.1.0 --plugin-enable=tk-inter fixarr.py

```

<br>

## 💡 CREDITS

<p style="text-align:center;" align="center">
   <a href="https://www.themoviedb.org">
  <img align="center" src="https://github.com/FIXARR/FIXARR/blob/279c46c7744bfdbb2e99dd802637cea65d2fdc3d/assets/tmdb.svg" height="200"/>
   </a>
</p>

## License

MIT
