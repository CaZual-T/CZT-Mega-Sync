# What is MegaCZT?
- MegaCZT utilizes a shared mega folder link to then download and install onto a client machine.
- It works by inputing a mega url, then downloading to the specified destination.
- One person needs a mega account so they can upload & share a folder. Then other users can use this tool to download that folder.
- This is to help those none tech savy friends finally install those mods you always talk about!
# Features:
- Auto Install/Detect Mega CMD
- Auto Set Path & Manual Set Path
- Browse Mods folder
- Auto download and install mod folder to proper location
- Progress bars, Log window.
## How setup as host (sync folder host)
- Share a folder on mega.
- Share the link generated with other users.
## How to use (sync folder client) (first time use/install)
- Download & Install MegaCZT.
- Run MegaCZT. *(As Administrator)*
- Paste shared folder link into MEGA Folder URL entry.
- Click auto path (for RoN) or Manual Path
- Click 'Install MEGA'
- Click 'Detect MEGA'
- Delete existing mod folder within destination path if it exists.
- Download.
## How to use (sync folder client) (existing install) 
- Run MegaCZT. *(As Administrator)*
- Paste the shared folder link into MEGA Folder URL entry. [OPTIONAL: only needed if the url changed]
- Click auto path (for RoN) or Manual Path [OPTIONAL: only needed if you intend to switch games/install location]
- Download.
# How to Install/First time use (In depth guide):
> [!IMPORTANT]
      - Requires a shared MEGA folder url+key. (the url that has both in one)<br>
      - Get this by sharing your folder on mega or getting the link from the owner of the shared folder.
- Run the installer and complete the installation process.
- Once installed, run the app as Administrator.
- Click "Install Mega" and wait for the process to complete.
- After installation, click "Detect Mega" to confirm it’s properly set up.
- Paste the shared MEGA folder link.
- Click "Auto Path". (currently only works for RoN)
  - It should automatically detect something similar to:<br>
    `D:\Program Files (x86)\Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`
- Click "Save Config".
- Before continuing, delete the folder currently holding all of your mods:
  - Exception: If it’s already named *mod.czt*, or you just dont have a mods folder to begin with, skip this step.
  - For example, mod.io has its own folder ~ delete the one holding the mods from other sites (the tool creates a new folder)<br>
     *DO NOT DELETE mod.io if you see it. I was just using it as an example.* 
>[!NOTE]
      - MegaCZT is hard coded to only update folders named mod.czt currently.<br>
      - This is due to my tool dynamically changing the folder name to the files url extension, and not the actual folder name. which is annoying.
- Finally, click "Download Folder" to begin downloading the mods.

## Sidenotes
+ The reason we delete the mod folder is because the tool looks for any exisitng mod.czt folders within the Destination path.<br>
+ If it already exists it clears it for updates etc. If the folder doesnt exist it can just create a new one automatically, But if your 3rd party mods folder isnt deleted then you'll end up with 2 folders holding mods.<br>
> [!CAUTION]
>       - Technically you could keep another folder named mods etc for personal mods that arent within the shared folder, but that could lead to conflicts if not managed properly.























































