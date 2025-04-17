VapeLabs Auto Bot _ COGUDROPS
An advanced automated bot for the TheVapeLabs airdrop platform, designed to perform battery tapping, complete daily missions, and manage multiple accounts efficiently. Features a visually enhanced terminal interface with a fixed ASCII banner and real-time status updates.
Register
Join TheVapeLabs platform to obtain your tokens:

Register here

Features

✅ Auto-Tapping Battery: Automatically taps when battery is below 50% (5 taps every 20 seconds) until it reaches 100%, then waits until it drops below 50% again.
✅ Multi-Account Support: Manages multiple accounts using token-based authentication, with seamless switching via arrow keys.
✅ Proxy Support: Rotates IPs using proxies from proxies.txt to avoid rate limiting.
✅ Daily Check-In Automation: Automatically completes daily check-ins for rewards.
✅ Automatic Mission Completion: Identifies and completes available tasks across all categories.
✅ Interactive Terminal UI: Features a fixed ASCII art banner, real-time status panel (uptime, total taps, successful taps), user info, tapping status, and scrollable logs.
✅ Real-Time Logging: Displays detailed logs with timestamps and status icons (✅, ❌, ⚠️, etc.) for all actions.
✅ Account Navigation: Switch between accounts using ← and → keys; exit with q.

Prerequisites

Node.js: Version 16 or higher (tested with v22.14.0). Download Node.js.
Git: To clone the repository. Download Git.
Terminal: A terminal that supports colors and resizing (e.g., Windows Terminal, PowerShell, or VS Code terminal).

Installation
Follow these steps to set up and run the bot:

Clone the Repository:
git clone https://github.com/cogumellumdao/VapeLABS.git
cd TheVapeLabs-Auto-Bot


Install Dependencies:Install the required Node.js packages:
npm install


Configure Tokens:Set up your TheVapeLabs tokens (obtained from the platform) using one of the following methods:
Option 1: Using tokens.txt (Recommended)
Create a tokens.txt file in the root directory and add one token per line:
token1_here
token2_here
token3_here


Configure Proxies (Optional):To avoid rate limiting, create a proxies.txt file in the root directory and add one proxy per line in the format ip:port or ip:port:username:password:
http://123.45.67.89:8080
http://username:password@ip:port


Run the Bot:Start the bot with:
node index.js



Usage
The bot launches an interactive terminal interface with the following components:

Fixed Banner: A stylized ASCII art banner at the top.
Status Panel: Displays uptime, number of accounts loaded, total taps, and successful taps.
User Info Panel: Shows account ID, username, points, and battery level.
Tapping Status Panel: Displays proxy, tapping status, battery level, and time left.
Log Panel: Scrollable logs with real-time updates and status icons (✅ for success, ❌ for errors, etc.).
Instructions Panel: Guides navigation and exit commands.

Controls

← (Left Arrow) / h: Switch to the previous account.
→ (Right Arrow) / l: Switch to the next account.
q / Ctrl+C: Quit the bot.

Battery Tapping Logic

Below 50%: Auto-taps (5 taps every 20 seconds) until 100%.
100%: Stops tapping and waits until battery drops below 50%.
50% to 99%: Waits until battery drops below 50% before resuming tapping.

Troubleshooting

Syntax Errors: Ensure the index.js file is not corrupted. Use the provided code if errors occur.
No Tokens Found: Verify that tokens.txt or .env contains valid tokens.
Rate Limiting (429 Errors):
Add more proxies to proxies.txt.
Increase delays in index.js (e.g., adjust setTimeout in performTapBurst).


Interface Issues: Use a terminal that supports ANSI colors and resizing (e.g., Windows Terminal).
API Errors: Check token validity or API URL (https://api.thevapelabs.net/v1.0).

Disclaimer
This project is for educational purposes only. Use at your own risk. The developers are not responsible for any consequences arising from the use of this bot.
License
This project is licensed under the MIT License - see the LICENSE file for details.

💎 Credits 💎 

CogumellumDROPS  COFFEE ADDRESS 😉
0x3Ecfa30D64A8f4c764d8D58F4F7d8203Bb7fACf0
