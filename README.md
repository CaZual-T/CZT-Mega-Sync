# What is MegaCZT?
- MegaCZT utilizes a shared mega folder link to then download and install onto a client machine.
- It works by inputing a mega url, then downloading to the specified destination.
- One person needs a mega account so they can upload & share a folder. Then other users can use this tool to download that folder.
- This is to help those none tech savy friends finally install those mods you always talk about!

# Features:
- Auto Install/Detect Mega CMD.
- Auto Set Path & Manual Set Path.
- Browse Mods folder.
- Auto download and install mod folder to proper location.
- Progress bars, Log window.
# How to Install/First Time Use Guide:
> [!IMPORTANT]
      - (Host) Requires a shared MEGA folder url+key. (the url that has both in one)<br>
      - (Host) Share folder on MEGA > Distribute the link (url) to users you want to sync with.<br>
      - (Client) The user that owns the shared folder will provide clients with the shared folder link (url).

## How setup as host (sync folder HOST)
- Share a folder on mega.
- Share the link generated with other users.
>[!NOTE]
      - HOSTS:<br>
      - MegaCZT is hard coded to only download mega folders named mod.czt currently.<br>
      - This is due to my tool dynamically changing the folder name to the files url extension, and not the actual folder name. which is annoying.

## How to use (sync folder CLIENT) (first time use/install)
- Download & Run MegaCZT_Installer.
- Open MegaCZT.
- Paste the shared folder link into the 'MEGA Folder URL' entry.
- Click "Auto Path" (currently only works for RoN) or Manual Path for other games/locations.
  - It should automatically detect something similar to:<br>
    `D:\Program Files (x86)\Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`
- Click 'Choco Install'. (wait for it to complete) (app will auto close and need relaunched to complete setup)
- Before downloading, delete the folder currently holding all of your mods:
  - For example, mod.io has its own folder ~ delete the one holding the mods from other sites (the tool creates a new folder)<br>
     *- DO NOT DELETE mod.io if you see it. I was just using it as an example.*
  - EXCEPTION(S): If your current folder is named *mod.czt*, or you dont have a mods folder to begin with, skip this step.
- <b>Click Download!</b>

## How to use (sync folder client) (existing mod.czt install) 
- Run MegaCZT. 
- Paste the shared folder link into MEGA Folder URL entry.      *- OPTIONAL: only needed if the url changed.*
- Click auto path (for RoN) or Manual Path.      *- OPTIONAL: only needed if you intend to switch games/install location.*
- Download.

### Sidenotes
+ The reason we delete the mod folder is because the tool looks for any exisitng mod.czt folders within the Destination path.<br>
+ If it already exists it clears it for updates etc. If the folder doesnt exist it can just create a new one automatically, But if your 3rd party mods folder isnt deleted then you'll end up with 2 folders holding mods.<br>
> [!CAUTION]
>       - Technically you could keep another folder named mods etc for personal mods that arent within the shared folder, but that could lead to conflicts if not managed properly.













































































