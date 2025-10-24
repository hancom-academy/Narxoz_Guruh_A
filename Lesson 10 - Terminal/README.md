🧱 1️⃣ Quick Recap: File & Navigation Basics

A short 30-min warm-up to make sure they’re confident.

Command	Description

cd	Changes the current directory. Example: cd Documents
cd ..	Goes one folder back (to parent directory).
cd ~	Goes straight to your home directory.
dir (Windows) / ls (Linux)	Lists files and folders in the current directory.
mkdir project	Creates a new folder named project.
rmdir foldername	Deletes an empty folder. (Use with care!)
del filename.txt	Deletes a file. (Windows)
move file.txt Documents	Moves a file to another folder.
rename old.txt new.txt	Renames a file.
cls (Windows) / clear (Linux)	Clears the screen.



---

⚙️ 2️⃣ Installing Programs via Terminal

🪟 If you’re using Windows

Option 1: Winget (Windows Package Manager)

(Built-in on Windows 10/11)

Command	Description

winget search vscode	Searches for an app (Visual Studio Code here).
winget install vscode	Installs the app directly.
winget list	Lists all installed programs.
winget upgrade --all	Updates all installed apps.
winget uninstall appname	Uninstalls a program.


Option 2: Chocolatey (Optional)

(If you install it first — good to just mention)

Command	Description

choco install googlechrome	Installs Google Chrome.
choco upgrade all	Updates all apps installed via Chocolatey.



---

🐧 If on Linux (Ubuntu/Debian style)

Command	Description

sudo apt update	Refreshes package info. Always run before installing.
sudo apt install vlc	Installs VLC player.
sudo apt remove vlc	Uninstalls VLC player.
sudo apt upgrade	Updates all installed packages.
apt list --installed	Shows all installed apps.


(Explain sudo means “superuser do” — gives admin permissions.)


---

💻 3️⃣ Cool “Hacker-Looking” & Useful Tricks

Command	Description

dir /s	Lists all files and subfolders inside current directory (looks intense 😎).
tree	Displays folders and subfolders in a tree view. (You may need to install it first — sudo apt install tree)
systeminfo	Shows system specs — OS, RAM, processor, etc.
ipconfig	Shows IP address and network details.
ping google.com	Checks if your internet connection works and measures response time.
tracert google.com	Traces the route data takes to reach Google’s servers. (Linux version: traceroute google.com)
netstat	Lists active network connections and ports.
tasklist	Shows all running processes (like Task Manager).
taskkill /PID <id>	Ends a process by its ID number.
color a	Changes terminal text color to green. (Fun Matrix-like look.)
title Hacker Terminal	Changes the terminal window title.
curl wttr.in	Displays live weather info in your terminal.
cls	Quick clear to look clean before “hacking” again 😎



---

🎯 4️⃣ Fun “Challenge” Ideas (End the Class With These)

Find your PC name: hostname

Check Wi-Fi details: netsh wlan show profiles

Display date/time: time and date

Make it look busy: dir /s, then open a new window and ping google.com -t

Bonus: curl parrot.live → animated parrot in your terminal 🦜

