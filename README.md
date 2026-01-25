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
- Press CTRL+SHIFT+L to open language menu.

# How to Install/First Time Use Guide:
> [!IMPORTANT]
      - (Host) Click ["HERE"](https://github.com/CaZual-T/CZT-Mega-Sync/tree/main?tab=readme-ov-file#how-to-use-megaczt-host) to learn how to generate a shared mega folder url+key.<br>
      - (Client) You will need a shared mega folder url. (obtain from whoever is hosting the folder)

# How to use MegaCZT [CLIENT] 
### First time use/Install:
- Download & Run MegaCZT_Installer.
- Open MegaCZT.
- Click 'Setup CLI'. (wait for it to complete) (app will auto close and need relaunched to complete setup)
  - Note that during install a powershell window will popup to install choco, DO NOT close, it will close on its own once complete.</br>
 > [!NOTE]
      > [ALT OPTION] You can download the cli yourself from [(https://mega.io/cmd)](https://mega.io/cmd) </br>
      > Once megaCMD is installed just click 'detect cli' within megaCZT
  <img width="352" height="105" alt="image" src="https://github.com/user-attachments/assets/494a7774-3bcb-4c8c-9341-c5a3d4718e54" />

- Paste a shared MEGA folder link into the MEGA Folder URL entry. (get this from whoever is hosting the folder)
  <img width="492" height="68" alt="image" src="https://github.com/user-attachments/assets/6a0c9365-d957-48a5-aad7-cb3dd6f3c9b0" />

- Click "Auto Path" (For users syncing Ready or Not folders) or Manual Path for other games/locations.
  > CZT Mod Manager Users: Press F2 to enable plugin mode. </br>
  > Then set custom path to {Drive}:\CZT Mod Manager\profile_mods < select that folder
  <img width="718" height="68" alt="image" src="https://github.com/user-attachments/assets/28cc97e1-fa8d-4014-98b5-781c1a226f6b" />

  - It should automatically detect something similar to:<br>
    `Program Files (x86)\Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`</br>
    `Program Files\Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`</br>
    `Steam\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`</br>
    `SteamLibrary\steamapps\common\Ready Or Not\ReadyOrNot\Content\Paks`</br>
- Save Config.
- <b>Click Download!</b>

### How to use MegaCZT anytime after initial setup:
- Run MegaCZT. 
- Paste a shared MEGA folder link into the MEGA Folder URL entry.      *- OPTIONAL: only needed if the url changed.*
- Download.
>[!CAUTION]
      - DOWNLOADING BEGINS A DIRECT FILE TRANSFER BETWEEN THE URL USED AND YOUR PC.<br>
      - ONLY DOWNLOAD/USE MEGA URLs FROM USERS THAT YOU TRUST!

<img width="836" height="508" alt="image" src="https://github.com/user-attachments/assets/5ddd4582-54ad-490b-85af-e862b6fd830e" />

# How to use MegaCZT [HOST]
- Locate your mods folder (Optional: you can use my tool ["CZT Mod Manager'](https://github.com/CaZual-T/CZT-Mod-Manager))</br>
  - Default location: /Program Files (x86)/Steam/steamapps/common/Ready Or Not\ReadyOrNot/Content/Paks/'Mods' ← SYNC</br>
  - CZT Mod Manager Users: Be sure to use the 'Ready or Not' folder within CZT Mod Manager/profile mods/'Ready or Not' ← SYNC</br>
- Upload the folder to mega or use mega sync (best option) (learn how to setup mega sync below)</br>
- Share the folder.</br>
- Share the link generated with other users.</br>

### MegaSync Setup:</br>
- Download megasync (desktop app) (https://mega.io/syncing)</br>
- Once installed click the Mega icon in the system tray/bottom right of your desktop task bar (red circle with M)</br>
- Click + Add Sync at the top</br>
<img width="342" height="543" alt="{3E5CA375-BB50-47E8-89D7-78EE155B8089}" src="https://github.com/user-attachments/assets/ad03467c-ede6-4b48-9310-b9481bfdfdd2" /> </br>

- This will allow you to select your mods folder and automatically sync to your mega drive. </br>
- Once setup, mega will automatically sync any file in that folder to your mega folder. </br>
- You can then get the link for that folder (go to your mega storage and right click to share and get link) </br>
- Now you can easily update without having to transfer all of your mods at one time.) </br>
<img width="107" height="32" alt="image" src="https://github.com/user-attachments/assets/4dce72e4-c144-4c30-b7dc-a7d2f20627c0" />

- Also, anytime you update your mods folder, your friends can run MegaCZT to download your shared folder and automatically install with the click of a button!
