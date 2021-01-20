# roundediconsgnome
install rounded icons for your activity bar in gnome 3
# Round icons for activity bar in gnome

round icons for the activy bar on gnome3:

## Requirments

trasnsparent bar recommended: [see this]([Transparent Top Bar (Adjustable transparency) - Estensioni per GNOME Shell](https://extensions.gnome.org/extension/3960/transparent-top-bar-adjustable-transparency/))

gnome extensions

## Enable hidden files

On file manager, go to home directory and click on the menu bar and then show hidden files

![](file:///home/alberto_gnome/Immagini/hiddenfiles.png)

## Create a new folder

on a free space right click and select `new folder` (or press shift+ctrl+N)

name the folder `.themes` and open it

create a folder inside of it (you can choose the name as you like)

open it and create another folder called `gnome-shell`

open it and then right click on the empty space and press `open in terminal`

on terminal type: `touch gnome-shell.css`

then close it.

## Modify css file

after closing the terminal return to the previously created gnome-shell directory, you should see the css file created:

![alt text](https://github.com/al6263/roundediconsgnome/blob/main/Screenshot%20from%202021-01-20%2014-10-43.png)

open it (I used mousepad)

after have opened copy this code to the file

`#panel {
 background-color: rgba(0, 0, 0, 0);
}

#panel .panel-button {
 background-color: rgba(255, 255, 255, 0.10);
 border-radius: 2em;
 color: black;
}

#panel .panel-button:hover {
 background-color: rgba(0, 0, 128, 0.5);
}

#panel .panel-button:active {
 background-color: rgba(0, 0, 128, 1);
}`

save it and close the file manager

## Gnome-tweaks

to apply the custom theme you need to have gnome-tweaks if you don't open a terminal and write:

`sudo apt install gnome-tweak-tool` (for debain based distros)

` sudo dnf install gnome-tweak-tool` (for fedora distros)

`sudo pacman -S gnome-tweaks` (for arch linux distros)

## Gnome-extensions

open gnome extensions and scroll down to `user themes` and enable it.

![alt text](https://github.com/al6263/roundediconsgnome/blob/main/estensioni.png)

##

## Apply custom theme

open gnome tweaks and select `appearance`

and then `shell`

open the menu and select your custom theme (you can recognize it because has the same name you chosen before)

![alt text](https://github.com/al6263/roundediconsgnome/blob/main/Screenshot%20from%202021-01-20%2014-27-22.png)

## Final result

you have done! this is the final resoult:

![alt text](https://github.com/al6263/roundediconsgnome/blob/main/pulsanti%20belli.png)
