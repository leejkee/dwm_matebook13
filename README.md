# dwm for my matebook13.
# cpu:i5 8265u 
# gpu:intel and nvidia mx 150
## install
```shell
git clone git@github.com:leejkee/dwm_matebook13.git
make && sudo make clean install
```
## message
- runs /home/ljk/scripts/autostart.sh when `startx`
- modify the funtion runAutoastart() in dwm.c to customize your path of `autostart.sh`
## shortcut
- win+F4 mute/unmute
- win+F6 turn up the volume
- win+F5 turn down the volume
- win+F1 turn down light
- win+F2 turn up light
## fonts
- noto-fonts-cjk
- wqy-microhei
- adobe-source-code-pro-fonts
- ttf-nerd-fonts-symbols
