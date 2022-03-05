# INSTALL

! testet for "VampireSurvivors" "v0.3.0c" !

## FILES
- copy *mod* folder in the same location as the assets folder and main.bundle.js
	...\steamapps\common\Vampire Survivors\resources\app\.webpack\renderer

## UI
- open *main.bundle.js* with a text editor of your choice
- search for.. UI.png
- add Content of the *data_ui.txt* file underneath this
![image](https://user-images.githubusercontent.com/10463138/156074231-b35eb0bf-cb6d-46c3-b069-6ac49c79fe22.png)
- save
- test if game can load main.bundle.js, 
	if you get a black screen, just undo the change with ctrl+z and check again if it is the right place.
	



## MAP
- open main.bundle.js with a text editor of your choice
- search for.. 'stageName': 'Green Acres',
- add the Content of the *data_map.txt* file as a new array element to it
![image](https://user-images.githubusercontent.com/10463138/156074529-c97c4686-910c-40c6-8ed3-b6b5cb8cce93.png)
- make sure there is a coma between the square brackets
- save
- test if game can load main.bundle.js, 
	if you get a black screen, just undo the change with ctrl+z and check again if it is the right place.

## tileset used
- Bokou https://forums.rpgmakerweb.com/index.php?threads/bokous-freesources-added-gothic-tileset.48613/
- Anokolisa https://anokolisa.itch.io/high-forest-assets-pack
- ? https://centrorpg.com/index.php?topic=14770.0 (RPMaker tileset pack)
- ? https://www.rpg-maker.fr/mv-tilesets.html (RPMaker tileset)

I have tried to follow the design of the original map.
