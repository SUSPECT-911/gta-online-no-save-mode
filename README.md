# gta-online-no-save-mode
AutoHotkey script to enable GTA Online No Save Mode by blocking Rockstar servers using Windows Firewall.
GTA Online – No Save Mode (AutoHotkey)
📌 Overview

This project provides an AutoHotkey script that enables No Save Mode in GTA Online by temporarily blocking Rockstar servers using Windows Firewall.

It allows you to turn No Save Mode ON/OFF instantly using keyboard shortcuts, without manually changing firewall settings.

⚙️ How It Works

Uses Windows Firewall (netsh advfirewall)

Blocks outgoing traffic to a specific server IP

Requires Administrator privileges

Automatically removes firewall rules when turned off or when the script exits

🎮 Use Case

Prevent GTA Online progress from being saved

Test gameplay without affecting stats

Temporary no-save sessions

Safe experimentation

🛠️ Requirements

Windows 10 / Windows 11

AutoHotkey (v1.x)

Administrator access

🚀 Installation & Usage (Step-by-Step)
1️⃣ Download AutoHotkey

Download AutoHotkey from the official website:
👉 https://www.autohotkey.com/download/ahk-install.exe

Install it normally.

2️⃣ Download the Script

Download or clone this repository

Extract the .ahk file to any folder

3️⃣ Run Script as Administrator

Right-click the .ahk file

Click Properties

Go to the Compatibility tab

Enable Run this program as administrator

Click Apply → OK

Now double-click the script to run it.

4️⃣ Hotkeys (In-Game or Anywhere)
Shortcut	Function
Ctrl + F9	Turn ON No Save Mode
Ctrl + F12	Turn OFF No Save Mode

A tooltip will appear confirming the status

Firewall rules are applied instantly

🧯 Safety & Failsafe

Firewall rule is automatically removed on exit

Prevents permanent internet blocking

Safe to close the script anytime

⚠️ Disclaimer

This project is intended for educational and personal testing purposes only.

Not affiliated with Rockstar Games

Use at your own risk

Online games may restrict network manipulation

The author is not responsible for bans, penalties, or data loss

Always follow the game’s Terms of Service.

