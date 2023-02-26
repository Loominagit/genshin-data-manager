# genshin-data-manager
A script used to download Genshin Impact (Android version) game files written in Python. Sorry if the code is a mess, because this is my first time using Python.

## How it works:
The script will take some files from your phone (it's the game version, nothing spooky I swear), and then it will download the game files. It's simple as that.

### Pre-requisities
- Python 3.10 (download it [here](https://python.org) if you are on Windows)
- Android platform-tools
  - Ubuntu: `sudo apt install android-sdk-platform-tools`
  - Arch Linux: `sudo pacman -Sy android-tools`
  - Windows: [Download it here](https://dl.google.com/android/repository/platform-tools-latest-windows.zip), then [set up the environment variable so the script can work](https://www.xda-developers.com/adb-fastboot-any-directory-windows-linux/)
- Around 30 GB of free space

### Steps:
1. Clone this repo (or just download the repo ZIP)
2. Go to `genshin-data-downloader`
3. Run the script using python
4. Follow the instructions
5. Wait until it's done downloading

## FAQs:
**Q:** How did you find the update link, like wtf?<br/>
**A:** It's a funny story. I got the update link from a download log, which is inaccessible without root permission. I opened it and thinking it was just a generic log like you see on every software. But turns out they left out the update link on the log, and from there you know what I'm about to do lol.

**Q:** How long did you make the script<br/>
**A:** I think it's around 2 hours, just to make the downloader work.

**Q:** WHY IS IT SO SLOW??<br/>
**A:** Because it's not multi-threaded, lol. Once I made it multi-threaded, the download process will be MUCH faster.

## TODO:
- [x] Working downloader
- [ ] Multithread download
- [ ] A way to copy game files to phone
- [ ] Resumable download
- [ ] Working updater
