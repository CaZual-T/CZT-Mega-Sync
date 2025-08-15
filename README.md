# What is MegaCZT?
- MegaCZT utilizes a shared mega folder link to then download and install onto a client machine.
- It works by inputing a mega url, then downloading to the specified destination.
- One person needs a mega account so they can upload & share a folder. Then other users can use this tool to download that folder.
- The whole point of this is so that you and your friends can all have the exact same mods installed without issue.

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

## How to use (sync folder CLIENT) (first time use/install)
- Download & Run MegaCZT_Installer.
- Open MegaCZT.
- Paste the shared folder link into the 'MEGA Folder URL' entry. (get this from whoever is hosting the folder)
- Click "Auto Path" (currently only works for RoN) or Manual Path for other games/locations.
  - It should automatically detect something similar to:<br>
    `D:\Program Files (x86)\Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`
- Click 'Choco Install'. (wait for it to complete) (app will auto close and need relaunched to complete setup)
- Before downloading, if you have an existing mod folder please rename it to mod.czt
  - EXCEPTION(S): If you dont have a mods folder to begin with, skip this step.
- <b>Click Download!</b>

## How to use (sync folder client) (existing mod.czt install) 
- Run MegaCZT. 
- Paste the shared folder link into MEGA Folder URL entry.      *- OPTIONAL: only needed if the url changed.*
- Click auto path (for RoN) or Manual Path for any location.      *- OPTIONAL: only needed if you intend to switch install location.*
- Download.

## How setup as host (sync folder HOST)
- Upload a folder named mod.czt on mega. (check out https://mega.io/syncing to make this super easy on yourself)
- Share the folder.
- Share the link generated with other users.
>[!NOTE]
      - HOSTS:<br>
      - MegaCZT is hard coded to only download mega folders named mod.czt currently.<br>
      - This is due to my tool dynamically changing the folder name to the files url extension, and not the actual folder name. which is annoying.
      - Also megaSYNC is useful for hosts. It links your folder to a folder on mega and updates live. No need to upload massive packs. 















































































