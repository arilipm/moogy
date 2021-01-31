# moogy
an x theme using various programs

> required:

*moved - see [INFO.md](https://github.com/setasorcer/moogy/blob/main/INFO.md) for more info*

> screenshot:

![Image](https://files.catbox.moe/nzyi2s.png)

> installation 4 nubz

start by cloning the repository

`git clone https://github.com/arilipm/moogy.git`

place the files in your home directory `~/`

replace "arili" with your username

--- 

and don't forget to mark the appropriate files

* .config/polybar/launch.sh

* .config/bspwm/bspwmrc

as executable! because i forgot

> troubleshooting

if the keybindings don't work, add

`sxhkd &`

to `.xinitrc` before `exec bspwm`

i also suppose your tty is broken

`loginctl` to identify your session

`loginctl terminate-session <id>` to kill it

> copyright

i hate copyright
