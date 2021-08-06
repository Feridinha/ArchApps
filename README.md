# ArchApps
Os comandos para instalar todos os meus aplicativos que eu uso no Arch linux.


### Install snap
```
git clone https://aur.archlinux.org/snapd.git
cd snapd
makepkg -si
sudo systemctl enable --now snapd.socket
sudo ln -s /var/lib/snapd/snap /snap
```

### Install brave
```
yay -S brave-bin
```

### Install vscode
```
git clone https://aur.archlinux.org/visual-studio-code-bin.git
cd visual-studio-code-bin
makepkg -si
```

### Install telegram
```
sudo pacman -S telegram-desktop
```
### Install nordvpn
```
git clone https://aur.archlinux.org/nordvpn-bin.git
cd nordvpn-bin.git
makepkg -si
```

### Install burpsuite
```
git clone https://aur.archlinux.org/burpsuite.git
cd burpsuite
makepkg -si
```
### Install zsh + oh-my-zsh
```
sudo pacman -S zsh
curl -L http://install.ohmyz.sh | sh
```

### Install flatpak
```
sudo pacman -S flatpak
```

### Install spotify
```
flatpak install flathub com.spotify.Client
```
##### Solução para o crash aleatório: Desativar notificações
