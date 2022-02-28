# INSTALL

! only for "VampireSurvivors" "0.2.13" !

## FILES
- copy *mod* folder in the same location as the assets folder and main.bundle.js
	...\steamapps\common\Vampire Survivors\resources\app\.webpack\renderer

## UI
- open *main.bundle.js* with a text editor of your choice
- search for.. var _0x5dccf9 = _0x465e1a;
- add Content of the *data_ui.txt* file underneath this
![image](https://user-images.githubusercontent.com/10463138/156074231-b35eb0bf-cb6d-46c3-b069-6ac49c79fe22.png)
- save
- test if game can load main.bundle.js, 
	if you get a black screen, just undo the change with ctrl+z and check again if it is the right place.
	



## MAP
- open main.bundle.js with a text editor of your choice
- search for.. [_0x26dcac[_0x465e1a(0x1e2)]]: [{
- copy above Content of the *data_map.txt* file
![image](https://user-images.githubusercontent.com/10463138/156074529-c97c4686-910c-40c6-8ed3-b6b5cb8cce93.png)
- make sure there is a coma between the square brackets
- save
- test if game can load main.bundle.js, 
	if you get a black screen, just undo the change with ctrl+z and check again if it is the right place.
