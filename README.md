# Installation
put contents into /.config/sublime-text-3/Packages/User
I prefer to clone this somewhere else and then symlink it in, something like:
```
cd ~/.config/sublime-text-3/Packages
ln -s ~/.synced_configs/st3 User
```

if package control has not been installed, install it using instructions found @ https://sublime.wbond.net/installation

when you install it, package control will find any missing packages and install them
