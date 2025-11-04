# hyprcfg

I miss gnome

    mkdir -p ~/.config/hypr/hyprlock
    ln $PWD/hyprland.conf ~/.config/hypr/hyprland.conf
    ln $PWD/hyprlock.conf ~/.config/hypr/hyprlock.conf

    yay -S hyprland kitty rofi waypaper hyprpaper hyprshot hyprlock

Lock screen images

    git clone git@github.com:ChillerData/Pictures.git /tmp/pics
    cp /tmp/pics/Wallpapers/CellegenBG.png ~/.config/hypr/hyprlock/background.png
    cp /tmp/pics/teeworlds/chiller/chiller.png ~/.config/hypr/hyprlock/profile.png
