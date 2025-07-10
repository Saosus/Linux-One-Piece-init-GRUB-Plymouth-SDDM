# GRUB configuration
1) Put the **GRUB_onepiece** file into `/boot/grub/themes/` directory
2) You need to download `Terminus` and `Thunderman` fonts (or whatever fonts you want)
3) GRUB need pf2 format fonts, so you can use command `sudo grub-mkfont -o <output pf2 file> <input font file>`
4) After settings, do `sudo grub-mkconfig -o /boot/grub/grub.cfg` command OR use grub-customizer
# Plymouth configuration
1) Put the **luffyNika** dir into `/usr/share/plymouth/themes`
2) Whatever gif you use (luffyNika/ already have one) you need to convert them into frames. Use that command: `ffmpeg -i luffyNika.gif animation%d.png`
3) You may need to config `luffyNika.script` file (for example `images_count` line, it depends on count of frames of your images)
# SDDM configuration
1) I use this guy theme as base: https://github.com/Keyitdev/sddm-astronaut-theme
2) So, as you download his repo, put the `one_piece.conf` file into `/usr/share/sddm/themes/sddm-astronaut-theme/Themes/` dir
3) Put the `png` and `mp4` files into `Background/` dir

And remember, you always can read manuals of GRUB and Plymouth configs or ask AI for help:) Because it's my first time make README description of my rice (and rice at all), and I don't know is it mostly understandable to set for most of people
