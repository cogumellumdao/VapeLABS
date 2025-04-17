![image](https://github.com/user-attachments/assets/2a0be17a-b6bb-4c87-9c7b-6b201f894095)

# VapeLabs Auto Bot

An automated bot for TheVapeLabs airdrop platform that handles battery tapping, daily missions, and account management with an enhanced terminal UI featuring a fixed ASCII banner and real-time status updates.

## Register

- Link : https://bit.ly/4imtfbw

## Features

-✅ Auto-tapping battery when below 50% until it reaches 100%

-✅ Multi-account support with token-based authentication

-✅ Proxy support for rotating IPs

-✅ Daily check-in automation

-✅ Automatic mission completion

-✅ Interactive terminal UI with fixed ASCII banner, real-time status (uptime, taps), and scrollable logs

-✅ Auto-switching between accounts for monitoring


## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/cogumellumdao/VapeLABS.git
   cd TheVapeLabs-Auto-Bot
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure your tokens (see Configuration section below)

4. Run the bot:
   ```bash
   node index.js
   ```

## Configuration

### How to get the TOKEN

Press F12 or enter developer mode
now CLICK ON ** NETWORK **
CLICK on ** Fetch/XHR **
Refresh the page by clicking F5
Wait for it to update as soon as ** get ** appears. Look for ** Authorization **

Copy everything except ** BEARER ** at the beginning we won't use it
Now just paste it into the ** token.txt ** folder on your computer

![image](https://github.com/user-attachments/assets/173c0c7a-1da0-45ef-86e1-60a792e7c1af)


### Token Setup

There are two ways to set up your VapeLabs tokens:

#### Option 1: Using tokens.txt file (Recommended)

Create a `tokens.txt` file in the root directory and add one token per line:

```
token1_here
token2_here
token3_here
```

### Proxy Setup (Optional)

Create a `proxies.txt` file in the root directory and add one proxy per line in the format `ip:port` or `ip:port:username:password`:

```
http://123.45.67.89:8080
http://username:password@ip:port
```

## Usage

The bot features an interactive terminal UI:

- Use **Arrow Keys** (← →) to navigate between accounts
- Press **Q** to quit the bot

### Battery Tapping Logic

- When battery is **below 50%**, the bot will automatically tap (5 taps every 20 seconds) until it reaches 100%
- When battery is **100%**, the bot will wait until it drops below 50% to start tapping again
- When battery is **between 50% and 100%**, the bot will wait until it drops below 50%

## Troubleshooting

- If you're experiencing rate limiting (429 errors), consider:
  - Adding more proxies to `proxies.txt`
  - Increasing the delay between requests

## Disclaimer

This project is for educational purposes only. Use at your own risk. The developers are not responsible for any consequences that may arise from using this bot.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Credits

CogumellumDROPS COFFEE ADDRESS 😉 ``` 0x3Ecfa30D64A8f4c764d8D58F4F7d8203Bb7fACf0 ´´´
