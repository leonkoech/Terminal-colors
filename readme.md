# Terminal Colors 

## Instructions
Preferably, download the zip and follow the instructions. You may also clone this repo, but that has not been tested yet. That said, feel free to go through the code and figure out what to edit.
`git clone https://github.com/leonkoech/Terminal-colors`

NOTE: Make sure to backup the files before doing this.
`cp .bashrc .bashrc.backup`
`sudo cp /etc/bash.bashrc /etc/bash.bashrc.backup`
`cp /etc/pacman.conf /etc/pacman.conf.backup`

Move required files where they are supposed to be (as root)

`mv bash.bashrc /etc/bash.bashrc`
`mv DIR_COLORS /etc/`
`mv .bashrc ~/.bashrc`

For Pacman 
`sed -i 's/#Color/Color/g' /etc/pacman.conf`
`pacman -Syu`

The setup is based off of Average Linux User's article. Visit to know more about customizing nano. [This is the link](https://averagelinuxuser.com/linux-terminal-color/)