# MemoArch
Aide mémoire pour arch


En COURS


------------------------  
Script Architect Cardiac  

sudo pacman -Sy git  
git clone https://github.com/Cardiacman13/Architect.git  
cd Architect  
./architect.sh  


----------  
Kernel-TKG  

git clone https://github.com/Frogging-Family/linux-tkg.git  
cd linux-tkg  
makepkg -si  

-----------  
Jakoolit Hyprland  

git clone https://github.com/JaKooLit/Arch-Hyprland.git  
cd Arch-Hyprland  
chmod +x install.sh  
./install.sh  


------------------
Pour Manette PS4 :  
dr4drv &

----------------------------
Mapping touche Hyprland

Keybind pour les workspaces :  
~/.config/hypr/configs/Keybinds.conf  

#Switch workspaces with mainMod + [0-9]  
bind = $mainMod, ampersand, workspace, 1  
bind = $mainMod, eacute, workspace, 2  
bind = $mainMod, quotedbl, workspace, 3  
bind = $mainMod, apostrophe, workspace, 4  
bind = $mainMod, parenleft, workspace, 5  
bind = $mainMod, minus, workspace, 6  
bind = $mainMod, egrave, workspace, 7  
bind = $mainMod, underscore, workspace, 8  
bind = $mainMod, ccedilla, workspace, 9  
bind = $mainMod, agrave, workspace, 10  

#Move active window to a workspace with mainMod + SHIFT + [0-9]  
bind = $mainMod SHIFT, ampersand, movetoworkspace, 1  
bind = $mainMod SHIFT, eacute, movetoworkspace, 2  
bind = $mainMod SHIFT, quotedbl, movetoworkspace, 3  
bind = $mainMod SHIFT, apostrophe, movetoworkspace, 4  
bind = $mainMod SHIFT, parenleft, movetoworkspace, 5  
bind = $mainMod SHIFT, minus, movetoworkspace, 6  
bind = $mainMod SHIFT, egrave, movetoworkspace, 7  
bind = $mainMod SHIFT, underscore, movetoworkspace, 8  
bind = $mainMod SHIFT, ccedilla, movetoworkspace, 9  
bind = $mainMod SHIFT, agrave, movetoworkspace, 10  
