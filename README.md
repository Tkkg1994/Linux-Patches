# What is this for?
This are all linux patches you can get on 3.18.y, 3.10.y and 3.4.y kernel.

I realised that it is kind of very boring to download all small patches on the www.kernel.org website. So I will upload here all new Linux versions, that you can download them just from here!

For example you got a 3.4.0 kernel and want to update it to latest linux mainstream, you have to download 108 files (at the moment). Here on this github page, you can just download them all with one click :)

# HOW TO patch my source:
Open your terminal, navigate to your source and copy the patchfiles into this direction. Then type: patch -p1 <(filename) --ignore-whitespace

# And what to do if I got .rej files?
This files are coming to the repo if a patch did not apply successfully. In this file you can see what should be changed and you have to manually fix it. The original file is always stored in the .orig file. So you always see what changed between the updates.
I recommand you to commit all changes, like: Linux 3.10.5 update and so on
