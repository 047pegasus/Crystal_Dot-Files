# Crystal_Dot-Files
My personal Crystal Linux dot files for setup ⚡.

# INSTALLATION COMMANDS:

'''
//Update system packages entirely
sudo pacman -Syu

//Install paru AUR helper.
sudo pacman -S --needed base-devel
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si

//Installing all dependencies for the rice to work
paru -S hyprland-git polkit-kde-agent dunst grimblast rofi rofi-emoji wl-clipboard wf-recorder wlogout grimblast-git hyprpicker-git hyprpaper-git xdg-desktop-portal-hyprland-git ffmpegthumbnailer tumbler wtype colord imagemagick swaylock-effects qt5-wayland qt6-wayland ripgrep waybar-hyprland-git micro google-chrome visual-studio-code-bin blueman catppuccin-gtk-theme-mocha catppuccin-cursors-mocha catppuccin-mocha-grub-theme-git nwg-look cava pavucontrol ranger zsh starship neovim viewnior noise-suppression-for-voice thunar thunar-archive-plugin file-roller terminus-font-ttf spotify

// Rebuilding font cache
fc-cache -rv  

'''
