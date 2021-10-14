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
### Install chatterino (7tv)
```
git clone --recurse-submodules https://github.com/SevenTV/chatterino7.git
sudo pacman -S qt5-base qt5-multimedia qt5-svg qt5-tools gst-plugins-ugly gst-plugins-good boost rapidjson pkgconf openssl cmake
cd chatterino7
mkdir build && cd build
cmake .. && make

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
sudo cp ~/chatterino7/build/bin/chatterino /bin
sudo cp ~/chatterino7/resources/icon.png /usr/share/icons/chatterino.png
sudo cp ~/chatterino7/resources/com.chatterino.chatterino.desktop /usr/share/applications/chatterino.desktop
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
### Install dunst
###### Iniciar automaticamente com o sistema 
```
sudo pacman -S dunst
```
### Install spotify
###### Instalar dunst ou desativar as notifcações.
```
snap install spotify
```

### Manipular local das novas janelas
![Janelas](https://img.vivaolinux.com.br/imagens/dicas/comunidade/Screenshot_20210403_155625.png)
