# LayerEdge Automation Bot

An automation tool designed to help users manage their LayerEdge light nodes efficiently with a convenient terminal-based dashboard interface.

## Features

- 🚀 Auto Ping for Light Node
- 💰 Automatic Daily Points Claim
- 📊 Real-time Points Tracking
- 🎯 Multi-wallet Support
- 💻 Interactive Terminal Dashboard
- 🎨 Colored Status Indicators
- 📱 Pagination for Multiple Accounts

## Prerequisites

Before running the bot, make sure you have:

- Node.js (v14 or higher)
- npm (Node Package Manager)
- A LayerEdge account (register with referral code: `VkWpMgC3`)

## Registration

1. Visit [LayerEdge Dashboard](https://dashboard.layeredge.io)
2. Enter the referral code: `7FYJLWy2`
3. Connect your wallet and complete the registration
4. Start earning points by running a light node!

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Galkurta/LayerEdge-BOT.git
```

2. Navigate to the project directory:

```bash
cd LayerEdge-BOT
```

3. Install dependencies:

```bash
npm install
```

4. Edit configuration:
   - Edit `data.txt` file in the root directory
   - Add your wallet addresses (one per line)

## Project Structure

```
LayerEdge/
├── main.js
├── data.txt
├── package.json
└── config/
    ├── banner.js
    ├── colors.js
    └── ...
```

## Usage

1. Start the bot:

```bash
node main.js
```

2. Controls:
   - ↑/↓: Navigate between wallets
   - ←/→: Change pages
   - Ctrl+C: Exit program

## Features Explained

### Auto Ping

- Automatically pings the LayerEdge network every configured interval
- Keeps your light node active and earning points
- Configurable ping interval

### Points Claiming

- Automatically attempts to claim daily points
- Tracks claim status and results
- Shows error messages if claim fails

### Dashboard Interface

- Clean and intuitive terminal interface
- Real-time status updates
- Color-coded status indicators
- Pagination for managing multiple wallets

### Error Handling

- Comprehensive error reporting
- Automatic retry mechanism
- Clear error messages

## Status Colors

- 🟢 Active: Node is running normally
- 🔴 Error: Node encountered an error
- 🟡 Starting: Node is initializing
- 🟢 Claimed: Points successfully claimed
- 🔴 Claim Failed: Failed to claim points

## Support & Links

- GitHub: [https://github.com/Galkurta](https://github.com/Galkurta)
- Telegram: [https://t.me/galkurtarchive](https://t.me/galkurtarchive)
- Referral Code: `7FYJLWy2`

## Contributing

Contributions are welcome! Please feel free to submit pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This bot is provided as-is, without any warranties. Users are responsible for their own actions and should use this tool responsibly.
