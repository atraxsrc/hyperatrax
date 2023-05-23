# hyperatrax
Ricing on an Arch, by the way.

## Installation
```shell
yay -S brave-bin fuse
sudo pacman -S gedit rofi zsh wget curl lsd bitwarden
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

### Add to .zshrc
Add the following line to your `.zshrc` file:
```shell
plugins=(sudo git history-substring-search colored-man-pages zsh-autosuggestions zsh-syntax-highlighting)
alias ls='lsd'
```

### Change sddm background
Copy the desired picture to:
```shell
/usr/share/sddm/themes/sdt/wallpaper.jpg
```
I find it easier to rename the stored picture to `originalwallpaper.jpg` and change the name to my desired picture to `wallpaper.jpg`.

### Change backgrounds in any version
Follow the same steps as above, but for the `hyprv_util` file located in `.config/HyprV/`.
```shell
~/.config/HyprV/backgrounds/$VER'-background-dark.jpg
~/.config/HyprV/backgrounds/$VER'-background.jpg
```

### Extras
Image enhancer/upscaler:
[https://github.com/upscayl/upscayl/releases](https://github.com/upscayl/upscayl/releases)
