## Useful terminal commands

### One colection of useful terminal commands

##### Pacman helpful commands

`sudo pacman -Qdt`  -----> This command will list the orphan packages on your system

`sudo pacman -Rns $(pacman -Qqdt)` -----> And this commando delete the orpahn packages

`sudo pacman -Syu` -----> Command for update system and packages

`sudo pacman -Syyuu` -----> This command update the packages and the system
##### Terminal 

`where <nameofprogram>` -----> This command show the path of programs on you machine

`cat <pathtofile>` -----> This commands show the content inside a file

##### Yay

`yay -c` -----> This command clears unused dependencies for yay packages
