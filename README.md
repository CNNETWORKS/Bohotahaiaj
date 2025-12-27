# Elite OSINT Telegram Bot

A premium Telegram bot with OSINT capabilities and admin panel.

## Features

- 🔍 Multiple OSINT tools (IMEI, IP, Email, Phone, Domain, etc.)
- 👑 Elite admin panel
- ✅ User registration system with admin approval
- 💰 Credits management
- 📊 Statistics and analytics

## Quick Deploy to Railway

1. **Create GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Elite OSINT Bot"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/osint-bot.git
   git push -u origin main
   ```

2. **Deploy to Railway**
   - Go to [railway.app](https://railway.app)
   - Login with GitHub
   - Click "New Project" → "Deploy from GitHub repo"
   - Select your repository

3. **Set Environment Variables** in Railway:
   ```
   BOT_TOKEN=8469907392:AAGVUGR1SR9eNVVx-Hl7X1jJNaQewzb_VZ8
   ADMIN_ID=5695514027
   ```

## Bot Commands

### User Commands
- `/start` - Register and start using the bot
- `/help` - Show help message
- `/credits` - Check your credits
- `/imei <number>` - IMEI lookup
- `/ip <address>` - IP address lookup
- `/email <email>` - Email validation
- `/phone <number>` - Phone number lookup
- `/domain <domain>` - Domain information
- `/instagram <username>` - Instagram lookup
- `/bin <number>` - BIN card lookup
- `/vehicle <number>` - Vehicle information
- `/freefire <id>` - Free Fire ID lookup
- `/paknumber <number>` - Pakistani number lookup

### Admin Commands
- `/admin` - Open admin panel
- `/approve <user_id>` - Approve user registration
- `/stats` - Show bot statistics
- `/broadcast <message>` - Send broadcast to all users
- `/users` - List all users
- `/pending` - Show pending users

## Requirements

- Node.js 18+
- Railway account
- GitHub account

## Support

For issues and support, contact the admin.

---

🚀 **Ready to deploy!** This bot is fully configured for Railway deployment.
