# blurlocker

### a simple screen locker for i3

this is a simple, four line shell scripts that uses i3lock and mogrify to screencap, blur and lock the screen. intended for use with i3.

## dependencies

`i3lock`
`imagemagick`

## installation

add these lines to your .i3/config: 
`bindsym $mod+l exec "~/.local/bin/fuzzy_lock.sh"
exec xautolock -time 15 -locker '~/.local/bin/fuzzy_lock.sh' &`
