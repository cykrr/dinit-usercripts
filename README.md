# krr's d-init user scripts

This is a collection of user scripts/services to handle the window manager subprocess (usually started from an `autostart.sh` script or directly from WM's config file). 

```
# ~/.config/hypr/hyprland.conf
...
exec-once = dinit -u --cgroup-path /run/user/1000 -d ~/.local/etc/dinit.d
...

```




| Service | Function |
| ------  | -------  |
| edp-off | Disables the laptop's monitor if HDMI screen is found (needs adjusting) |
| waybar  | Status bar |
| mpvpaper | (animated) wallpaper manager |
| mpd | Music Player Daemon|
| pipewire | Audio server |
| mako | notification-daemon |
| mate-polkit | polkit integration |
| blueman-applet | BT applet |

everything else is either bork'd or half ass work

