# hyprcfg

I miss gnome

    mkdir -p ~/.config/hypr/hyprlock
    ln -s $PWD/hyprland.conf ~/.config/hypr/hyprland.conf
    ln -s $PWD/hyprlock.conf ~/.config/hypr/hyprlock.conf
    ln -s $PWD/hyprpaper.conf ~/.config/hypr/hyprpaper.conf

    yay -S hyprland kitty rofi waypaper hyprpaper hyprshot hyprlock

Lock screen images

    wget https://raw.githubusercontent.com/ChillerData/Pictures/refs/heads/master/teeworlds/chiller/chiller.png -O ~/.config/hypr/hyprlock/profile.png
    wget https://raw.githubusercontent.com/ChillerData/Pictures/refs/heads/master/Wallpapers/CellegenBG.png -O ~/.config/hypr/hyprlock/background.png
