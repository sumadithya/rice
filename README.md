# Hess' Rice
This is my rice for Void Linux,I have created this so that if anyone wants to use my config files they can.

## Contents
+ Sample
+ My Programs
+ Installation

## Sample
<img src="https://github.com/Hess2906/rice/blob/master/rice.png" width="100%"></img> 

## My Programs
+ editor: vim
+ email: neomutt
+ files: ranger
+ terminal: Luke's fork of st "https://github.com/LukeSmithxyz/st"
+ pdf: zathura, zathura-djvu, zathura-pdf-mupdf

## Installation
If you want to install mu config I suggest 2ways 
+ 1. Make a new user and copy my files 
+ 2. Copy them to your own user, I reccomend the former since you do not have to backup your files

### Dependencies
i3-gaps polybar ranger vim neofetch zathura zathura-djvu zathura-pdf-mupdf

#### New User - Reccomended
This will allow you to test the configuration without having to backup your current one

1. create a new user, make sure to add it to some groups: -m makes home. -G adds groups -s chooses shell (my config only has a bashrc, so I reccomend bash)
```
useradd -m -G <groups> -s /bin/bash <username>
```  
2. set the pasword for the user
```
passwd <username>
```
3. login as the user
```
su <username>
```
4. change to the their /home directory and clone my repo
```
cd ~; git clone https://github.com/Hess2906/rice.git
```
5. copy it to the /home
```
cp ~/rice/* ~/; cp ~/rice/.* ~/
```
#### Current user
good if you haven;t yet cofnigured your system

1. Change to your /home directory and clone the repository
```
cd ~; git clone https://github.com/Hess2906/rice.git
```
2. backup if you want to
```
mkdir ~/Backup; cp ~/* ~/Backup/; cp ~/.* ~/Backup
```
3. copy files
```
cp ~/rice/* ~/; cp ~/rice/.* ~/
```
