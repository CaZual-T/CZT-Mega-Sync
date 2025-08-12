- Run the installer and complete the installation process.
- Once installed, run the app as Administrator.
- Click "Install MegaCMD" and wait for the process to complete.
- After installation, click "Detect MegaCMD" to confirm it’s properly set up.
- Paste your shared MEGA folder link.
- Click "Auto Path". (currently only works for RoN)
  It should automatically detect something similar to:
  ↳  *D:\Program Files (x86)\Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks*
  ↳  Let me know if it doesn’t work.
- Click "Save Config".
- Before continuing, delete the folder currently holding all your mods:
  ↳  For example, mod.io has its own folder — delete the one holding the mods from other sites (the tool creates a new folder based on your shared mega folders name.) (Note its hard coded to only accept ~nexus_mods as the folder name currently)
  ↳  Exception: If it’s already named *Your Shared Mega Folder Name*, or you just dont have a mods folder to begin with, skip this step.
- Finally, click "Download Folder" to begin downloading the mods.
The reason we delete the mod folder is because the tool looks for any exisitng folders within the Destination path. If it already exists it clears it for updates etc. If it doesnt exist it can just create a new one automatically, But if your 3rd party mods folder isnt deleted then you'll essentially end up with double mod folders. This is because the tool is designed to only delete the folder that matches the shared mega folder.

Right Now auto detect only works for RoN. More Gamnes will be added in the future.
