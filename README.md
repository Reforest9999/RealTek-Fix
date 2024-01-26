# RealTek-Fix
This works for realtek devices with jack detection issues, under linux kernel. Last tested on kernel 6.6.10

Under /etc/modprobe.d/alsa-base.conf

add the following line 
```options snd-hda-intel model=dell-headset-multi```
