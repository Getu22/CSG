
Conan Exiles Server GUI

![image](https://github.com/Getu22/CSG/assets/163321426/2217f541-85e8-41f9-924a-0b7b41383cec)

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

Written in Python and compiled into C with Nuitka.


