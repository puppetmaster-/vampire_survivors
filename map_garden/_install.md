# INSTALL

! testet for "VampireSurvivors" "v0.3.1c" !

## PREPARATION
It is not absolutely necessary but simplifies the insertion of the UI and MAP code.
- open *main.bundle.js* with a text editor of your choice (Windows nodepad isn't the ideal editor for this usecase)
- format code with Javascript formater
- replace 
`, this[` with
```
, 
						this[
```
- save
- test if game can load *main.bundle.js*, 
	if you get a black screen, just undo the change with ctrl+z and check again if it is the right place.

## FILES
- copy *mod* folder in the same location as the assets folder and main.bundle.js
	...\steamapps\common\Vampire Survivors\resources\app\.webpack\renderer

## UI
- open *main.bundle.js* with a text editor of your choice
- search for.. UI.png
- add Content of the *data_ui.txt* file at this position

_not formated_

![image](https://user-images.githubusercontent.com/10463138/156902003-dfa0690a-33e5-4257-bf62-1f817c8ac5ba.png)

_formated_

![image](https://user-images.githubusercontent.com/10463138/156902435-c349bb55-c578-427e-bb11-5672c1db0652.png)

- save
- test if game can load main.bundle.js, 
	if you get a black screen, just undo the change with ctrl+z and check again if it is the right place.
	

## MAP
- open main.bundle.js with a text editor of your choice
- search for.. 'stageName': 'Green Acres',
- add the Content of the *data_map.txt* file as a new array element to it

_not formated_

![image](https://user-images.githubusercontent.com/10463138/156902338-df1b458f-7092-4597-a4a7-eae57c24ba91.png)

_formated_

![image](https://user-images.githubusercontent.com/10463138/156902729-8268e448-f21c-40ad-ac10-fefd14507a12.png)
- save
- test if game can load main.bundle.js, 
	if you get a black screen, just undo the change with ctrl+z and check again if it is the right place.

## tileset used
- Bokou https://forums.rpgmakerweb.com/index.php?threads/bokous-freesources-added-gothic-tileset.48613/
- Anokolisa https://anokolisa.itch.io/high-forest-assets-pack
- ? https://centrorpg.com/index.php?topic=14770.0 (RPMaker tileset pack)
- ? https://www.rpg-maker.fr/mv-tilesets.html (RPMaker tileset)

I have tried to follow the design of the original map.
