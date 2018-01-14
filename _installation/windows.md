---
title: Installing on Windows
position: 3
---

<img class="doc-img" src="images/windows.png" alt="Windows" style="width: 75px;"/>

MusicBot can be installed on Windows 7, 8, and 10 too, though it requires installing some programs on your computer first.

1. Install Python 3.5+. For the best results, install <a href="https://www.python.org/ftp/python/3.5.4/python-3.5.4.exe" target="_blank">Python 3.5.4</a>.
2. During the setup, tick `Install launcher for all users (recommended)` and `Add Python 3.5 to PATH` when prompted.
3. Install <a href="http://gitforwindows.org/" target="_blank">Git for Windows</a>.
4. During the setup, tick `Use Git from Git Bash only`, `Checkout Windows-style, commit Unix-style endings`, and `Use MinTTY (the default terminal MSYS2)`.
5. Open Git Bash by right-clicking an empty space inside of a folder (e.g My Documents) and clicking `Git Bash here`.
6. Run `git clone https://github.com/Just-Some-Bots/MusicBot.git MusicBot -b master` in the command window that opens.

If you do not clone the bot using Git, and instead download the ZIP file from GitHub and attempt to run it, you will receive an error.
{: .warning }

After doing that, a folder called `MusicBot` will appear in the folder you opened Git Bash in. [Configure](#guidesconfiguration) your bot, then run `update_dependencies.bat` to update your dependencies, then `runbot.bat` to start the MusicBot.
