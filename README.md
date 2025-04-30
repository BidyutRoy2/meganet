# Meganet Auto Mining Bot

This bot allows you to automatically participate in Meganet's bandwidth sharing program, earning points that may be valuable for future airdrops. The bot connects to Meganet's servers and tracks your point accumulation in real-time.

## Features

## Register : https://t.me/hiddengemnews/12878

- Automatic connection to Meganet's bandwidth sharing network
- Real-time tracking of points earned
- Persistent connection with automatic reconnection
- Detailed logging of all activities
- Clean console display with up-to-date statistics

## Prerequisites

- Node.js (v14 or newer)
- npm (comes with Node.js)
- A Meganet wallet address and ID

## Installation

1. Clone this repository:
```bash
git clone https://github.com/BidyutRoy2/meganet.git
cd meganet
```

2. Install dependencies:
```
npm install
```

3. Open Meganet Dashboard (CTRL+SHIFT+C) & `Network` & Reload Page

![image](https://github.com/user-attachments/assets/c9c086e6-f7b2-4a63-ad7b-fafebf748f65)


4.  Config File With Your Address & ID - (CTRL+X+Y+ENTER) To Save
```
nano config.txt
```

```
WALLET_ADDRESS=Your EVM Wallet Address
WALLET_ID=Your Wallet ID
```

Start the bot

```
npm start
```

The bot will automatically:
- Connect to Meganet's WebSocket server
- Join the bandwidth sharing channel
- Periodically check and update your point statistics
- Display your current point status in the console

## Disclaimer

This bot is provided for educational purposes only. Use at your own risk. The developers are not responsible for any potential issues that may arise from using this bot, including but not limited to account restrictions, loss of points, or any other negative consequences.
