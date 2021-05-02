# ArchApps
Os comandos para instalar todos os meus aplicativos que eu uso no Arch linux.


###  Install snap
```
git clone https://aur.archlinux.org/snapd.git
cd snapd
makepkg -si
sudo systemctl enable --now snapd.socket
sudo ln -s /var/lib/snapd/snap /snap
```

###  Install brave
```
sudo snap install brave
```

###  Install vscode
```
git clone https://aur.archlinux.org/visual-studio-code-bin.git
cd visual-studio-code-bin
makepkg -si
```

###  Install telegram
```
sudo snap install telegram-desktop
```
