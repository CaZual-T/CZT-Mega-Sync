# What is MegaCZT?
- MegaCZT utilizes a shared mega folder link to then download and install onto a client machine.
- It works by inputing a mega url, then downloading to the specified path.
- One person needs a mega account so they can upload & share a folder. Then other users can use this tool to download that folder.
- This is to help those none tech savy friends finally install those mods you always talk about!
# Features
- Auto Install/Detect Mega CMD
- Auto Set Path & Manual Set Path
- Browse Mods folder
- Auto download and install mod folder to proper location
- Progress bars, Log window.
# How to Install/Use MegaCZT
- Run the installer and complete the installation process.
- Once installed, run the app as Administrator.
- Click "Install Mega" and wait for the process to complete.
- After installation, click "Detect Mega" to confirm it’s properly set up.
- Paste your shared MEGA folder link.
- Click "Auto Path". (currently only works for RoN)
  - It should automatically detect something similar to:
  -  *D:\Program Files (x86)\Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks*
  -  Let me know if it doesn’t work.
- Click "Save Config".
- Before continuing, delete the folder currently holding all your mods:
  - *Note: You can keep your original mods folder in the situation that maybe you want to use mods/files that arent included within the shared folder.*
    - *Be warned that this could lead to conflicts with mods within the mod.czt folder. It's up to the user to manage that if they choose to keep multiple mod folders.*
  - For example, mod.io has its own folder — delete the one holding the mods from other sites (the tool creates a new folder based on your shared mega folders name.)
    - DO NOT DELETE mod.io if you see it. i was just using it as an example.   
  - Notes:
    - MegaCZT is hard coded to only update folders named mod.czt currently. This is because otherwise it will dynamically change your folder name to the files url extension, and not the actual folder name.
  - Exception: If it’s already named *mod.czt*, or you just dont have a mods folder to begin with, skip this step.
- Finally, click "Download Folder" to begin downloading the mods.
  - The reason we delete the mod folder is because the tool looks for any exisitng folders within the Destination path. If it already exists it clears it for updates etc. If it doesnt exist it can just create a new one automatically, But if your 3rd party mods folder isnt deleted then you'll essentially end up with double mod folders. This is because the tool is designed to only delete the folder that matches the shared mega folder.










