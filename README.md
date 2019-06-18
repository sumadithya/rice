### Hess' Rice
This is my rice for Void Linux,I have created this so that if anyone wants to use my config files they can.
# Contents
My Programs
Installation
Screenshots

# My Programs
editor=vim
email=neomutt
files=ranger
terminal=lukes fork of st "https://github.com/LukeSmithxyz/st"

## Installation
If you want to install these I reccomend 2ways 1. Make a new user and copy my files 2. Copy them to your own user, I reccomend the former since you do not have to backup your files

# Dependencies
i3-gaps polybar ranger vim

# New User - Reccomended
This will allow you to test the configuration without having to backup your current one

1. create a new user, make sure to add it to some groups
useradd -m -G <groups> -s <shell> <user>
  
2. set the pasword for the user
passwd <user>

3. login as the user
su <user>

4. change to the their /home directory and clone my repository
cd ~; git clone https://github.com/Hess2906/rice.git

5. copy it over
cp ~/rice/* ~/; cp ~/rice/.* ~/
# Current user
good if you haven;t yet cofnigured your system

1. Change to your /home directory and clone the repository
cd ~; git clone https://github.com/Hess2906/rice.git

2. backup if you want to
mkdir ~/Backup; cp ~/* ~/Backup/; cp ~/.* ~/Backup

3. copy files
cp ~/rice/* ~/; cp ~/rice/.* ~/

## Screenshots
