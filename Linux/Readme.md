# No sound
```
It seems to be that this is issue is reported in Ubuntu kernel 5.3.0-41 and -42, you can go into details in this Bug report

Anyway the easiest way to fix it is to:

    Edit /etc/modprobe.d/alsa-base.conf as root and add options snd-hda-intel dmic_detect=0 at the end of this file by writing this on the terminal:

    echo "options snd-hda-intel dmic_detect=0" | sudo tee -a /etc/modprobe.d/alsa-base.conf

    Edit /etc/modprobe.d/blacklist.conf as root and add blacklist snd_soc_skl at the end of the file by writing this on the terminal:

    echo "blacklist snd_soc_skl" | sudo tee -a /etc/modprobe.d/blacklist.conf

    Restart the computer


```
