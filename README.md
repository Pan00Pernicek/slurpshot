# slurpshot
Screenshot script for sway with bemenu, native wayland, forked to work better for my personal use.

The script opens a bemenu that let's you choose the area for the screenshot to be taken. Afterwards you can view, open or discard the screenshot. Make it executable and copy it to your PATH or execute it with ./slurpshot

You can easily edit it to change the screenshot directory, the viewer or anything else.

It depends on bemenu, grim, imv, jq and slurp.

This fork of Slurpshot is designed for sortof theme. You may edit bemenu parameters in the script to make the design suite your setup (see man bemenu).

Currently the menu displays coordinates and process names for each container to select, this is not very beautiful but neccesary to identify the correct container. If someone has a better solution for that, please commit.
