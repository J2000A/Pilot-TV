# Pilot-TV
Pilot-TV is a project from the gliding club "Segelflugclub Lauf-Lillinghof (EDQI)" where a Raspberry Pi 4 is used to display a combination of the Arrival/Departure Times from Vereinsflieger together with a view of Glidertracker. The Rasperry Pi runs all the time as it is also used as FLARM Receiver (http://wiki.glidernet.org/wiki:raspberry-pi-installation). The screen is connected via a long HDMI and only has to be turned on. You can store the html files either locally or on your website.

TODOs
1) Create iframe as admin in Vereinsflieger https://www.vereinsflieger.de/member/admin/fb_creator.php
2) Insert iframe in flightTimes.html (see comments)
3) Adjust flightTimes.html (see comments)
4) Adjust frames.html (see comments)
5) Adjust Rasperry Pi congig.txt (hdmi_force_hotplug, hdmi_edid_filename, overscan) https://www.raspberrypi.org/documentation/configuration/config-txt/video.md
6) Autostart Chromium in flullscreen on startup https://linux.tips/tutorials/how-to-auto-start-chromium-in-full-screen-mode-to-a-website-url-on-ubuntu-os
7) Set frames.html as default start page in Chromium http://write.flossmanuals.net/chromium/setting-startup-and-start-page-options/
8) Reboot Rasperry Pi automatically every night https://gist.github.com/jritsema/d358f31bcc83f5bb479a
