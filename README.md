# Conjure Set Editor
Version of Magic Set Editor made for the Conjure Uncollectible Card Game.

# Installation
1. Click on the green "Code" button, then click on "Download ZIP".
2. Extract the ZIP file, then open the resulting folder.
3. Open the subfolder named `fonts`. It contains several `.ttf` files. Select them all, right-click on one of them, then click "Install". If the "Install" option is not available, double-click on each of the files. It should open a program with an "Install" button somewhere.
4. If you already had a previous version of CSE, move or copy all other subfolders into your existing CSE folder, allowing overwrite. Otherwise, this folder acts as a stand alone installation.
5. Open the program by double-clicking on the "magicseteditor.exe" file.
6. Click on the "New Set" button, select the "Conjure" game, select the "Main" template, then click "Ok".
7. By default, the cards will be displayed at a huge size. Go to the "Edit" menu, then "Preferences...", then "Display" tab. Set the "Zoom" value to something like 40% so you can see the entirety of the card. (You can manually type a value in the box.)
8. By default, the program will export card images at 600 DPI, which is a very high printing resolution. If you want to bump that to 1200 DPI (which is complete overkill but hey you do you), set the "Export" value to 200%. Then move to the "Internal" tab and set the "Internal Scale" value to 200%. This will quadruple the size of your set files.

# Use
While on the "Card" tab, you can edit the values on the card directly by clicking on them.

Some values are not obvious to find. for example the box for the lore text is in this red area:

![lore](https://github.com/G-e-n-e-v-e-n-s-i-S/Conjure-Set-Editor/blob/main/readme_images/lore.png)

It will become bigger once you have written text inside.

The color of the frame should adapt automatically to the mana cost, but if you want to change it manually, click somewhere here:

![frame](https://github.com/G-e-n-e-v-e-n-s-i-S/Conjure-Set-Editor/blob/main/readme_images/frame.png)

To change to shape of the border, click here:

![border](https://github.com/G-e-n-e-v-e-n-s-i-S/Conjure-Set-Editor/blob/main/readme_images/border.png)

To change the type of stat boxes, click here:

![stats](https://github.com/G-e-n-e-v-e-n-s-i-S/Conjure-Set-Editor/blob/main/readme_images/stats.png)

There are some additional customization options in the "Style" and "Set info" tabs.

If you want to make popout art, that is, parts of the art that jump in front of the frame, you can watch this tutorial here:

https://www.youtube.com/watch?v=oc6Fy8_BkKo&ab_channel=CajunAvenger

If you want to add keywords, they are located in the following file:

Conjure-Set-Editor/data/conjure.mse-game/keywords

Open it with a text editor, then look at how existing keywords a formatted to add yours.
Always make a backup of your keyword file, as when you'll want to update CSE, you might overwrite it, loosing your modifications.

To export renders of your cards, go to "File" menu, then "Export", then "All card images..."

If you have problems with this, come ask questions on the Discord server:
https://discord.gg/t3tetd5YMc
