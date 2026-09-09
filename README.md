# Backup de configs de KDE Plasma
Para restaurar:
1. Posicionarse en la carpeta del repo
2. 
```bash
cp config/* ~/.config/ && killall plasmashell && kstart plasmashell
```
3. 
```bash
mkdir -p ~/.config/fastfetch
cp fastfetch/* ~/.config/fastfetch
```
