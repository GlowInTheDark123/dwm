# My personal build of dwm

## Features
- terminal swallowing 
- 8 different window layouts
- manual window gaps rearragment
- heavy-use programs bound to keys
- sticky windows
- other cool stuff

## Installation
```bash
git clone https://github.com/GlowInTheDark123/dwm.git
cd dwm
```
You can now edit the ```config.mk``` file to choose which programs you want bound to keys:

Example:
```makefile
BRAVE = y
VIRTMANAGER = n
LF = y
GODOT = n
RETROARCH = y
```

You can now compile and install dwm
```bash
sudo make clean install
```
