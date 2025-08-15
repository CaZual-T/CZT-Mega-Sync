# What is MegaCZT?
- MegaCZT utilizes a shared mega folder link to then download and install onto a client machine.
- It works by inputting a mega url, then downloading to the specified destination.
- One person needs a mega account so they can upload & share a folder (host).<br> 
      - Then other users can use this tool to download and install that folder (client).
- The whole point of this is so that you and your friends can all have the exact same mods installed without issue at the click of a button.

# Features:
- Auto Install/Detect Mega CMD.
- Auto Set Path & Manual Set Path.
- Browse Mods/Logs/CLI folder.
- Auto download and install mod folder to proper location.
- Simple UI with Progress bars, Log window, and easy to use buttons with tooltips.
- Update MegaCZT from within the app (no need to download from github)
- Persistent config.

# How to Install/First Time Use Guide:
> [!IMPORTANT]
      - (Host) Scroll to bottom for setup and how to generate a shared mega folder url+key.<br>
      - (Client) Valid sharerd mega folder url. (obtain from whoever is hosting the folder)

# How to use MegaCZT [CLIENT] 
### First time use/Install:
- Download & Run MegaCZT_Installer.
- Open MegaCZT.
- Click 'Choco Install'. (wait for it to complete) (app will auto close and need relaunched to complete setup)
        - Note that during install a powershell window will popup to install choco, DO NOT close, it will close on its own once complete.
- Paste a shared MEGA folder link into the MEGA Folder URL entry. (get this from whoever is hosting the folder)
- Click "Auto Path" (For users syncing Ready or Not folders) or Manual Path for other games/locations.
  - It should automatically detect something similar to:<br>
    `Program Files (x86)\Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`<br>
    `Program Files\Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`<br>
    `Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`<br>
    `SteamLibrary\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`
- Save Config.
- Before downloading, if you have an existing mod folder please rename it to mod.czt
  - EXCEPTION(S): If you dont have a mods folder to begin with, skip this step.
- <b>Click Download!</b>

### How to use MegaCZT anytime after initial setup:
- Run MegaCZT. 
- Paste a shared MEGA folder link into the MEGA Folder URL entry.      *- OPTIONAL: only needed if the url changed.*
- Click auto path (for RoN) or Manual Path for any location.      *- OPTIONAL: only needed if you intend to switch install location.*
- Download.
>[!CAUTION]
      - DOWNLOADING BEGINS A DIRECT FILE TRANSFER BETWEEN THE URL USED AND YOUR PC.<br>
      - ONLY DOWNLOAD/USE MEGA URLs FROM USERS THAT YOU TRUST!

<img width="837" height="537" alt="{E336ADD2-7153-4003-9C69-5DC8D4A6B04A}" src="https://github.com/user-attachments/assets/101fc213-e9d9-4818-832e-bd2957ad25c2" />

# How to use MegaCZT [HOST]
- Create a folder named mod.czt
- Upload the folder to mega or use mega sync (see more on mega sync below) 
- Share the folder.
- Share the link generated with other users.

MegaSync Setup:
- Create a folder named mod.czt (for Ready or Not put this folder next to mod.io @ \Program Files (x86)\Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks)
<img width="673" height="200" alt="{6048EBEA-DD03-4A76-A45B-589293376AC6}" src="https://github.com/user-attachments/assets/43b76e9b-78b2-4030-b1d4-997dc6167d1c" />

- Download megasync (desktop app) (https://mega.io/syncing)
- Once installed click the Mega icon in the system tray/bottom right of your desktop task bar (red circl with M)
- Click + Add Sync at the top
<img width="342" height="543" alt="{3E5CA375-BB50-47E8-89D7-78EE155B8089}" src="https://github.com/user-attachments/assets/ad03467c-ede6-4b48-9310-b9481bfdfdd2" />

- This will allow you to select your mod.czt folder and automatically sync to your mega drive.
- Once setup, mega will automatically sync any file in that folder to your mega folder. You can then get the link for that folder (go to your mega storage and right click to share and get link) and easily update without having to transfer all of your mods at one time.)
<img width="94" height="33" alt="{4ACB2843-9920-461D-AE18-31BF3F3605A3}" src="https://github.com/user-attachments/assets/593c8cb2-c7a8-4900-a9bd-1f4f54b285dc" />

- Now anytime you update your mods folder, your friends can run MegaCZT to download your shared folder and automatically install a copy to their pc with the click of a button.
>[!NOTE]
      - HOSTS:<br>
      - MegaCZT is hard coded to only download mega folders named mod.czt currently.<br>
      - This is due to my tool dynamically changing the folder name to the files url extension, and not the actual folder name. which is annoying.















































































