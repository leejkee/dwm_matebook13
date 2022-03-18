# dwm for my matebook13.
 cpu:i5 8265u 
 gpu:intel and nvidia mx150(Please use the nvidia-dkms and linux-lts, just a suggestion.)
## patches
You can download these from the website suckless.org, using `wget`(Recommanded).
- dwm-alpha-20201019-61bb8b2.diff(透明)
- dwm-uselessgap-20211119-58414bee958f2.diff
- st-alpha-0.8.2.diff(used in st)
## install
```shell
git clone git@github.com:leejkee/dwm_matebook13.git
make && sudo make clean install
```
## message
- Run dwm:you should create the ~/.xinitrc, and `echo "exec dwm" > .xinitrc`.
- `autostart.sh`: runs /home/ljk/scripts/autostart.sh when `startx`
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
