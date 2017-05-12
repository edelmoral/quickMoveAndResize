## INSTALLATION

* execute in this directory as regular user:
```        
$ plasmapkg --type kwinscript -i .
```
* create custom shortcut with this command:
```
qdbus org.kde.KWin /Scripting loadScript ~/.kde/share/apps/kwin/scripts/quickMoveAndResize/contents/code/main.js; qdbus org.kde.KWin /Scripting start
```
Path to main.js can differ on your system, check it!

