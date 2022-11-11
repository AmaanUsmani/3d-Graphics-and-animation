Importing models and scene into UE5 : Exported all objects from blender as an .fbx file , importing the .fbx into the environment folder of UE5's content drawer

Issues while importing into UE5 : 
--Flipped Normals for most of the models causing them to break down
--Very Glitchy Floor (because of the very high poly count(600,000) due to displacement and subdivision modifier in blender)
--Unnatural lighting levels

How the above mentioned issues were solved :
--Had to go into face orientation mode in blender and flip the normals of the models that were breaking down in UE5
--Had to remake the entire floor tile design to reduce poly count
--Deleted lights while exporting into UE5

Extra things before animating :
--Added light sources from UE5 to give appropriate scene lighting
--Changed textures and materials of most objects to give a more realistic feel
--Added emission for the torches and acid

Animation procedure :
--Picked a music audio to match the theme of the scene
--Picked the number of shots needed to match the audio (6)
--Added camera actors for each shot, added keyframes at the start and end of every shot with camera placements covering most objects in the scene
--Rendered the frames
--Combine the frames into a video and timing the audio with it
