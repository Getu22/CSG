
Conan Exiles Server GUI

![image](https://github.com/Getu22/CSG/assets/163321426/502e8f36-cba8-4b7b-b162-97f298e2ff28)

Current Features:

A backup is created and compressed into a ZIP file upon shutdown.

Option for periodic backups (e.g., game_backup_1.db) as ZIP files, such as automatically every hour.

CPU cores and priority assignment are possible.

Notifications for game updates and mod updates, with an option to set the server to automatically restart after 5 minutes.

Port accessibility tests are available.

The public IP is displayed, and clicking on it copies the address.

If the server is running with an active PID, settings can be adjusted, and they will be automatically applied upon the next restart.

A scheduler automatically restarts the server at set times, for example, every 12 hours if "RestartCount per Day" is set to 2.

The player list and player count are queried via A2S every 60 seconds.

Restart warnings are sent via RCON as a broadcast to alert players (if RCON enabled & configured)



I am currently working on: 
The Discord ServerControl part under "Settings" is not yet fully implemented.

The initial server installation process is not 100% clean...you have to install the serverfiles and then close the gui and open it again


Written in Python and compiled into C with Nuitka.


Installation BUG -> if you want to install the serverfiles -> you have to download the steamcmd.exe over https://steamcdn-a.akamaihd.net/client/installer/steamcmd.zip
and copy the steamcmd.exe into the same folder. Then its possible to install the Serverfiles.
After you installed the Serverfiles you have to stop and then close and re-open the GUI again.

The alternative way to install the serverfiles is to use the official Version from Toolguy: [https://forums.funcom.com/t/conan-exiles-dedicated-server-launcher-official-version-1-7-5-beta-1-7-7/21699/3210](https://forums.funcom.com/t/conan-exiles-dedicated-server-launcher-official-version-1-7-8-beta-1-7-9/21699)

After you installed the serverfiles you can use my GUI - please dont run both Serverguis at the same time!

To report bugs or if you have questions, you can reach me over Discord at: https://discord.gg/ysgdkwp3GH

Discordname: Getu|ADMIN

