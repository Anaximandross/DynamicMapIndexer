#DynamicMapIndexer
Hello all! So I was recently working on a port for a popular game mode that utilizes a large number of custom positions 
related to static structures on the map. I got tired of manually placing the the markers, so instead I created something
to do it for me! This script goes through the map you're on, and it creates dynamically named markers at the location of 
the desired buildings. Currently, I have the script configured to mark:  
-Radio Towers  
-Certain Military Buildings  
-Industrial Facilities 
-Certain Port components  
-Airfields    
Once the building is created, the script will create a marker at the location of the building. This marker is then stored 
in an array with a relevant title (_factoryArray, _militaryBaseArray, _portArray, _radioArray, and _airfieldArray. These 
arrays are stored as _markername_position.This script is very easily configurable to search for whichever building you want 
to find, as well as change the color of the markers (currently all set to blue), the type of marker (depends on the building type), 
etc.     

This script is compatible with all Vanilla Maps, as well as the major CUP maps (I didn't add in the small maps, but they are 
simple to add in. Open the script and scroll to the near bottom. Simply add a case for the map name you want). All you need to do 
is add the script and initServer.sqf to your mission file, load it up, and you're good to go! I already configured the script to search
for the specific CUP buildings, but it is possible that I missed a few. If so, please let me know, or you can also add them in the script 
manually. I provided comments to guide you along.         

Credits: Full credit goes to @Asaayu for doing the heavy lifting on the script!  
Permissions: Anyone is welcome to use this script, just please provide credit and/or a link back to this page.    

Happy hunting!
