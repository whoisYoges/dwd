# dwd
Dmenu Wallpaper Downloader (Automate wallpaper downloading using dmenu)

- dwd is a bash script to download wallpapers (in bulk) according to the user input and order.
- downloads high quality wallpaper from [wallhaven](https://wallhaven.cc).
- opens your default image viewer after downloading the wallpapers to modify (edit/delete unwanted) the pictures.
- saves final wallpapers in `$HOME/Pictures/Wallpapers/Dwd/` directory.

### Dependencies
1. dmenu

### Optional Dependencies
1. libnotify (Only to get notification)

### Installation
Get [dwd](dwd) in your \*nix machine, make it executable, place it in path and run `dwd` from anywhere.
```
git clone https://github.com/whoisYoges/dwd.it
cd dwd/
chmod +x dwd
sudo mv dwd /usr/local/bin/
cd ..
rm -rf dwd/
```

### Uninstallation
```
sudo rm /usr/local/bin/dwd
```
