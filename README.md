## You do not need this environment to generate your own modpacks. This is just to keep track of the system assets in case i need to regenerate, and to give you an Example of how to setup  

install the humanizer and humanizer_import plugins into the 'addons' folder  
make sure both are enabled in the project settings  
from the dropdown select 'Humanizer Import' -> 'Equipment' -> 'Import All'  
ignore the errors  
then under Generate Zip you can select a pack from the dropdown to export (will be saved in the export folder) or create your own pack  

sidenote, you dont actually need the import_settings.json to generate valid resources, but these have custom config like display name and bone attachments. when you run the 'purge generated' it will not remove them.  
