
# 🎯 Discord Global Sniper Bot

A powerful Discord bot that automatically monitors all servers and detects various types of codes, gift cards, and promotional materials across multiple platforms.

## ⚠️ IMPORTANT DISCLAIMER

**This bot is for educational purposes only. Using this bot may violate Discord's Terms of Service. Use at your own risk.**

## 🎁 What This Bot Can Detect & Snipe

- 🎮 **Discord Nitro Gift Links** - Automatically claims Nitro gifts
- 🎬 **Netflix Gift Cards** - Detects Netflix redemption codes
- 🎵 **Spotify Premium Codes** - Finds Spotify gift codes
- 📦 **Amazon Gift Cards** - Identifies Amazon redemption codes
- 🎮 **Gaming Codes** - Steam keys, Epic Games, Xbox, PlayStation codes
- 🟣 **Twitch Prime Codes** - Twitch and Prime Gaming codes
- 📱 **Mobile Platform Codes** - Google Play and Apple/iTunes gift cards
- 🎟️ **General Promo Codes** - Various promotional codes and coupons
- 🔐 **Account Credentials** - Login details (email:password format)
- 💰 **Crypto Addresses** - Bitcoin, Ethereum, and other crypto wallets

## 🚀 Quick Setup

### Step 1: Get Your Bot Token

1. Go to [Discord Developer Portal](https://discord.com/developers/applications)
2. Create a new application or use an existing one
3. Go to the "Bot" section
4. Copy your bot token and make the confing.json to support the shit.

### Step 2: Add Bot to Servers

Use any of these methods to add the bot to Discord servers:

#### Method 1: Generate Invite Link
```
!invite_bot
```
This creates a general invite link you can use anywhere.

#### Method 2: Server-Specific Invite
```
!invite_bot SERVER_ID_HERE
```
Replace `SERVER_ID_HERE` with the actual server ID.

#### Method 3: Auto-Join from Invite
```
!join https://discord.gg/INVITE_CODE
```
The bot will generate an invite link to join that specific server.

#### Method 4: Mass Deployment
```
!mass_invite SERVER_ID1 SERVER_ID2 SERVER_ID3
```
Generate multiple invite links at once.

## 🎯 Bot Commands

### Control Commands
- `!snipe_enable` - Enable global monitoring across all servers
- `!snipe_disable` - Disable global monitoring
- `!snipe_status` - Show current status and statistics
- `!snipe_help` - Display all available commands

### Server Management
- `!snipe_servers` - List all connected servers
- `!snipe_exclude_server [ID]` - Exclude a server from monitoring
- `!snipe_include_server [ID]` - Include a server back in monitoring
- `!leave [SERVER_ID]` - Make bot leave a specific server

### Utility Commands
- `!snipe` - Generate a random promotional code (demo)
- `!snipe_stats` - Show detailed sniping statistics
- `!join <invite_link>` - Get bot invite for a server
- `!invite_bot [server_id]` - Generate bot invite link
- `!mass_invite [ids...]` - Mass deployment links

## ⚡ Features

- **Ultra-Fast Detection**: 0.5-second claim rate for maximum speed
- **Multi-Platform Support**: Detects 10+ different code types
- **Auto-Claiming**: Automatically attempts to claim detected codes
- **Real-Time Notifications**: Get instant alerts when codes are found
- **Global Monitoring**: Monitors all servers the bot has access to
- **Smart Exclusions**: Exclude specific servers from monitoring
- **Mass Deployment**: Easy setup across multiple servers

## 📊 Performance Stats

- **Detection Speed**: Sub-second code detection
- **Success Rate**: Optimized for maximum claim success
- **Server Capacity**: Can monitor unlimited servers simultaneously
- **Code Types**: 50+ regex patterns for comprehensive detection

## 🛠️ Advanced Configuration

### Enable Aggressive Mode
```
!snipe_enable
```
This activates:
- ✅ All code type detection
- ⚡ 0.5-second claim rate
- 🎯 Auto-claiming everything
- 📱 Instant notifications

### Exclude Specific Servers
```
!snipe_exclude_server 123456789012345678
```

### View Real-Time Statistics
```
!snipe_stats
```

## 🔧 Technical Details

### Dependencies
- `discord.py` - Discord API wrapper
- `aiohttp` - Async HTTP client for API calls
- `re` - Regex pattern matching for code detection

### Rate Limiting
- **Nitro Claims**: 0.5 seconds between attempts
- **Other Detections**: Real-time monitoring
- **API Calls**: Optimized to avoid Discord rate limits

### Regex Patterns
The bot uses advanced regex patterns to detect:
- URL-based gift links
- Alphanumeric codes
- Formatted promotional codes
- Account credentials
- Cryptocurrency addresses

## 🎮 Getting Started Example

1. **Start the bot**: Click Run in Replit
2. **Add to a server**: Use `!join https://discord.gg/example`
3. **Enable monitoring**: Send `!snipe_enable`
4. **Check status**: Send `!snipe_status`
5. **Watch it work**: The bot will automatically detect and claim codes!

## 📱 Need Help?

**Contact me on Discord: `xhvuuu`**

I can help you with:
- Setting up the bot properly
- Troubleshooting issues
- Custom configurations
- Adding the bot to specific servers
- Optimizing detection patterns

## ⚠️ Important Notes

1. **Discord ToS**: This bot may violate Discord's Terms of Service
2. **Use Responsibly**: Only use in servers where you have permission
3. **Rate Limits**: The bot respects Discord's API rate limits
4. **Detection Only**: Some codes may already be claimed by others
5. **Educational Purpose**: This is primarily for learning about Discord bots

## 🔐 Security

- Bot token is stored securely in Replit Secrets
- No user data is stored permanently
- All API calls use proper authentication
- Rate limiting prevents abuse

## 📈 Success Tips

1. **Add to Active Servers**: More activity = more potential codes
2. **Enable Quickly**: Use `!snipe_enable` as soon as bot joins
3. **Monitor Status**: Check `!snipe_stats` regularly
4. **Stay Updated**: Bot automatically updates detection patterns
5. **Use Mass Deployment**: Add to multiple servers with `!mass_invite`

---

**Made with ❤️ for the Discord community**

*Remember: Always respect server rules and Discord's Terms of Service*

**Ready to start sniping? Click Run and let's go! 🎯**
