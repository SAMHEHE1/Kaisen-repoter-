# 🚀 Mass Reporter Bot

A powerful and advanced Telegram bot for mass reporting with image support and enhanced functionality.

## ✨ Features

- 🖼️ **Image Support** - Beautiful Telegraph images for all menus
- 🤖 **Mass Reporting** - Advanced reporting with multiple reasons
- ⏱️ **Configurable Intervals** - Set custom report intervals (1-30s)
- 🔑 **Session Management** - Smart session rotation and cooldown
- 👑 **Premium System** - Time-based user access control
- 📊 **Real-time Status** - Live monitoring and statistics
- 🛡️ **Flood Protection** - Advanced anti-flood mechanisms
- 🎯 **Multiple Report Reasons** - Spam, Violence, Pornography, Fake

## 🚀 Quick Deploy

[![Deploy to Heroku]("https://dashboard.heroku.com/new?template=https://github.com/Samarth-1206/Kaisen-repoter")](https://dashboard.heroku.com/new?template=https://github.com/Samarth-1206/Kaisen-repoter)

## 📋 Environment Variables

### Required Variables
\`\`\`env
BOT_TOKEN=your_bot_token_here
ADMIN_USER_ID=your_telegram_user_id
API_ID=your_api_id
API_HASH=your_api_hash
\`\`\`

### Image URLs (Telegraph)
\`\`\`env
WELCOME_IMAGE_URL=https://telegra.ph/file/your_welcome_image.jpg
STATUS_IMAGE_URL=https://telegra.ph/file/your_status_image.jpg
SESSION_IMAGE_URL=https://telegra.ph/file/your_session_image.jpg
REPORT_IMAGE_URL=https://telegra.ph/file/your_report_image.jpg
PREMIUM_IMAGE_URL=https://telegra.ph/file/your_premium_image.jpg
\`\`\`

### Reporting Settings
\`\`\`env
REPORT_INTERVAL=5              # Seconds between reports (1-30)
MAX_REPORTS_PER_SESSION=10     # Max reports per session
SESSION_COOLDOWN=300           # Session cooldown in seconds
\`\`\`

### Social Links
\`\`\`env
SUPPORT_GROUP=https://t.me/your_support
UPDATE_GROUP=https://t.me/your_updates
YOUTUBE_CHANNEL=https://youtube.com/@your_channel
DEVELOPER_USERNAME=YourUsername
\`\`\`

## 🎯 How to Get Telegraph Images

1. Go to [telegra.ph](https://telegra.ph)
2. Create a new post
3. Upload your images
4. Copy the image URLs
5. Add them to your environment variables

## 📱 Commands

- `/start` - Start the bot with beautiful interface
- `/add_prm @user 7d` - Add premium user (Admin only)
- `/add_session session_string` - Add session string (Admin only)

## ⚙️ Advanced Features

### Smart Reporting
- **Multiple Reasons**: Spam, Violence, Pornography, Fake Account
- **Configurable Intervals**: 1s to 30s between reports
- **Session Rotation**: Automatic session management
- **Flood Protection**: Advanced anti-flood mechanisms

### Session Management
- **Cooldown System**: Prevents session overuse
- **Usage Tracking**: Monitor session performance
- **Auto-Recovery**: Handles session errors gracefully

### Premium System
- **Time-based Access**: Hour/Day based premium access
- **Auto-Expiry**: Automatic premium user cleanup
- **Admin Controls**: Full premium user management

## 🛠️ Installation

1. **Clone Repository**
   \`\`\`bash
   git clone https://github.com/yourusername/mass-reporter-bot
   cd mass-reporter-bot
   \`\`\`

2. **Install Dependencies**
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

3. **Set Environment Variables**
   \`\`\`bash
   cp .env.sample .env
   # Edit .env with your values
   \`\`\`

4. **Run Bot**
   \`\`\`bash
   python main.py
   \`\`\`

## 🔧 Configuration

### Report Intervals
- **1s**: ⚡ Ultra Fast (High Risk)
- **3s**: 🚀 Fast (Medium Risk)
- **5s**: ⭐ Recommended (Balanced)
- **10s**: 🛡️ Safe (Low Risk)
- **15s**: 🐌 Very Safe (Very Low Risk)
- **30s**: 🔒 Ultra Safe (Minimal Risk)

### Session Cooldown
- Default: 300 seconds (5 minutes)
- Prevents session overuse
- Adjustable based on needs

## 📊 Monitoring

The bot provides real-time monitoring:
- Active sessions count
- Available sessions
- Running tasks
- Success/failure rates
- Session usage statistics

## ⚠️ Important Notes

- Use responsibly and follow Telegram ToS
- Don't abuse the reporting system
- Keep your session strings secure
- Monitor your bot's activity regularly

## 🆘 Support

- 💬 Support Group: [Join Here](https://t.me/your_support)
- 🔄 Updates: [Follow Here](https://t.me/your_updates)
- 📺 YouTube: [Subscribe Here](https://youtube.com/@ycur_channel)
- 👨‍💻 Developer: [kaisen](https://t.me/ixigio)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Made with ❤️ by Sujoy™**
