# hyperatrax
Ricing on a Arch btw

## Installs
```
yay -S brave-bin fuse
sudo pacman -S gedit rofi zsh wget curl lsd bitwarden
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
### Add to .zshrc
plugins=(sudo git history-substring-search colored-man-pages zsh-autosuggestions zsh-syntax-highlighting)
alias ls='lsd'

### Change ssdm background

Copy desired picture to 
```
/usr/share/sddm/themes/sdt/wallpaper.jpg
```
I find it easier to rename the stored picture to *originalwallpaper.jpg* abd change the bane to ny desired picture to *wallpaper.jpg*

### Change backgrounds in any version

Same steps as above but in hyprv_util file located in .config/HyprV/
```
~/.config/HyprV/backgrounds/$VER'-background-dark.jpg
~/.config/HyprV/backgrounds/$VER'-background.jpg
```


### Extras

https://github.com/upscayl/upscayl/releases # Image enhancer
