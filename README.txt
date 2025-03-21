# Merging Alacrity with Jext
1. Generate Jext resource pack for JAVA and GEYSER
	https://spartacus04.github.io/jext-reborn/
2. Have the extract version of Alacrity and Jext Resources and merge them
	- Copy the pack.mcmeta into the extracted Alacrity
	- Copy the Jext files into extract Alacrity  (except for pack.mcmeta and pack.png)
	- (skip the 2 disc files conflict)
3. Go inside that merged directory, select all, and zip
	(This will make sure your zip contains the contents at root dir instead of a folder that contains them)
4. Convert that new resource-pack.zip to mcpack
	- https://modifiedcommand.github.io/ConvertJavaTextureToBedrock/
	- Name it resource-pack.mcpack
5. Transfer files from the Jext mcpack to our new resource-pack.mcpack
	- Open them both using zip archive open
	- Transfer:
		- mappings
		- textures/item_texture.json
		- sounds/sound_definitions.json
	- Rename in our new resource-pack.mcpack
		- sounds/records => sounds/jext