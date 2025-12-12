# Riddy Webhook Manager

<div align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue" alt="Platform">
  <img src="https://img.shields.io/badge/Version-1.0.0-green" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License">
</div>

## 🚀 Overview

Riddy Webhook Manager is a professional desktop application that simplifies Discord webhook management. Send messages, update existing posts, and manage all your webhooks from a beautiful, intuitive interface.

![Application Screenshot](screenshot.png)

## ✨ Features

- **📤 Send Messages**: Send text files directly to Discord via webhooks
- **🔄 Update Messages**: Edit existing Discord messages with new content
- **🔗 Webhook Management**: Add, edit, and organize multiple webhooks
- **📝 File Editor**: Built-in text editor with mention tracking
- **👁️ Real-time Preview**: See exactly what will be sent to Discord
- **📊 Mention Analytics**: Track user, role, and channel mentions
- **🎨 Modern UI**: Dark theme with glass effect and smooth animations
- **📁 File Management**: Create, edit, and delete text files directly

## 📥 Download & Install

### **Direct Download**
Download the latest release from the [Releases section](https://github.com/yourusername/Riddy-Webhook-Manager/releases).

**System Requirements:**
- Windows 10/11 (64-bit)
- 50MB free disk space
- Internet connection for Discord connectivity

### **Installation**
1. Download `Riddy-Webhook-Manager-v1.0.0.exe`
2. Run the installer
3. Follow the setup wizard
4. Launch the application

## 🎯 Quick Start

1. **Add Your First Webhook:**
   - Click the "Webhooks" tab
   - Click "Add Webhook"
   - Enter a name and your Discord webhook URL

2. **Create or Add Text Files:**
   - Place `.txt` files in the application directory
   - Or use the built-in file creator

3. **Send Your First Message:**
   - Go to the "Send File" tab
   - Select a file and webhook
   - Click "Send to Discord"

## 📚 Usage Guide

### Sending Files
1. Navigate to the "Send File" tab
2. Select a text file from the dropdown
3. Choose a webhook destination
4. Preview the content in real-time
5. Click "Send to Discord"

### Updating Messages
1. Go to the "Update Message" tab
2. Paste a Discord message link
3. Select new content from a text file
4. The app will auto-detect the correct webhook
5. Click "Update Message"

### Managing Webhooks
- **Add**: Click "Add Webhook" button
- **Edit**: Click on any webhook to edit details
- **Delete**: Use the delete button on each webhook
- **Preview**: Hover over webhooks to see URL previews

### File Management
- **Create**: Click "Add File" in the Files tab
- **Edit**: Click any file to open the built-in editor
- **Delete**: Use the delete button on each file
- **Preview**: See character counts and mentions

## 🛠️ Technical Details

- **Built with**: Python, PyWebView, Requests
- **File Format**: Supports `.txt` files only
- **Encoding**: UTF-8
- **Webhook Format**: Discord API webhook URLs
- **Message Limits**: Automatically splits long messages (>4096 chars)

## ⚙️ Configuration

The application stores configuration in:
- `webhooks.csv` - Your saved webhook URLs
- Application directory - Your text files

## 🔒 Security Notes

- Webhook URLs are stored locally in plain text
- No data is sent to external servers except Discord
- All operations happen on your local machine
- The application only connects to Discord's API

## 🤝 Contributing

While this is primarily a pre-built application, feedback and issues are welcome. Please use the Issues section to report bugs or suggest features.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Troubleshooting

**Common Issues:**

1. **"Invalid webhook URL" error**
   - Ensure the URL starts with `https://discord.com/api/webhooks/`
   - Check that the webhook hasn't been deleted in Discord

2. **Message not sending**
   - Check your internet connection
   - Verify the webhook is still valid
   - Ensure the file isn't empty

3. **Can't update message**
   - Make sure you have the correct message link
   - The webhook must be in your saved list
   - You need permission to edit the message in Discord

**Need Help?**
Open an issue on GitHub with:
- What you tried to do
- What error you received
- Screenshots if possible

## 📈 Changelog

### v1.0.0 - Initial Release
- ✅ Send text files to Discord via webhooks
- ✅ Update existing Discord messages
- ✅ Webhook management (add/edit/delete)
- ✅ Built-in file editor
- ✅ Real-time preview with mention tracking
- ✅ Modern dark theme UI
- ✅ Windows installer

## 🙏 Acknowledgments

- Discord for their webhook API
- PyWebView team for the excellent desktop framework
- All contributors and testers

---

<div align="center">
  <sub>Made with ❤️ for the Discord community</sub><br>
  <sub>If you enjoy this tool, consider starring the repository!</sub>
</div>
