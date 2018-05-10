# deluge-FBTExecute

### How to build:
if you want the very latest release, you can build the plugin from source.

You will need:
- git
- a version of python that matches your deluge version (2.7 by default)

##### Instructions:
- in a command window, type
```
    git clone https://github.com/RjSachse/deluge-FBTExecute.git
    cd deluge-FileBotTool
    git checkout develop
```

- then to build the plugin, on linux/osx type:
```
    python2.7 setup.py bdist_egg  # replace with 2.6 if your deluge uses python 2.6
```
   or on windows:
```
    py -2.7 setup.py bdist_egg
```
- The new .egg file located in the `dist/` folder is now ready to be added to deluge.
