# Blur Toolz - Discord Account Manager

<div align="center">
  <img src="data/pack.ico" alt="Blur Toolz Logo" width="64" height="64">
  
  [![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
  [![PyQt6](https://img.shields.io/badge/PyQt6-GUI-green.svg)](https://pypi.org/project/PyQt6/)
  [![License](https://img.shields.io/badge/License-Private-red.svg)]()
</div>

## 📋 Overview

Blur Toolz is a comprehensive Discord account management application developed by @zyex1z. It provides tools for Discord account generation and token validation with a modern, user-friendly GUI interface.

## ✨ Features

### 🔧 Tool Selection
- **Account Generator**: Create new Discord accounts automatically
- **Account Checker**: Validate existing Discord tokens

### 🎯 Token Checker
- **Single Token Validation**: Check individual Discord tokens
- **Bulk Token Checking**: Validate multiple tokens at once
- **Auto-cleanup**: Option to remove invalid tokens after checking
- **Real-time Console Logs**: Monitor checking progress

### 🏭 Account Generator
- **Automated Account Creation**: Generate Discord accounts with custom settings
- **Rate Limiting**: Built-in protection against API limits
- **Desktop Notifications**: Get notified when generation completes
- **VPN Integration**: Supports VPN services for better performance
- **License System**: Secure authentication with expiration tracking

### 🎨 User Interface
- **Modern Dark Theme**: Sleek and professional appearance
- **Real-time Status Updates**: Live progress tracking
- **Configuration Management**: Persistent settings storage
- **Application Logs**: Detailed operation logging

## 🖼️ Screenshots

### Main Tool Selection
![Tool Selection](https://via.placeholder.com/600x400/2b2b2b/ffffff?text=Select+Tool+Interface)

### Token Checker Interface
![Token Checker](https://via.placeholder.com/600x400/2b2b2b/ffffff?text=Token+Checker+Interface)

### Account Generator
![Account Generator](https://via.placeholder.com/600x400/2b2b2b/ffffff?text=Account+Generator+Interface)

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- Windows OS (recommended)
- Internet connection

### Dependencies
```bash
pip install PyQt6 pymongo requests httpx zendriver notifypy psutil
```

### Setup
1. Clone or download the repository
2. Install required dependencies
3. Configure `config.json` with your settings
4. Run the application:
```bash
python gui.py
```

## ⚙️ Configuration

The `config.json` file contains important settings:

```json
{
    "check_ratelimit": true,
    "notify": true,
    "notification_icon": "data/pack.ico",
    "mail_api": "https://api.incognitomail.co/",
    "mail_domain": "blur-toolz.shop",
    "save_tokens": true
}
```

### Configuration Options
- `check_ratelimit`: Enable rate limiting protection
- `notify`: Enable desktop notifications
- `notification_icon`: Path to notification icon
- `mail_api`: API endpoint for email services
- `mail_domain`: Domain for generated emails
- `save_tokens`: Save valid tokens to file

## 📁 Project Structure

```
V1.0/
├── gui.py              # Main application file
├── config.json         # Configuration settings
├── tokens.txt          # Token storage file
├── data/               # Application assets
│   ├── pack.ico        # Application icon
│   ├── download (2).ico
│   └── tick.svg        # Success indicator
└── README.md           # This file
```

## 🔐 Security Features

- **Hardware ID Verification**: Secure user authentication
- **License Key System**: Time-based access control
- **MongoDB Integration**: Secure user data storage
- **Rate Limiting**: Protection against API abuse
- **Encrypted Communications**: Secure data transmission

## 💡 Usage

### Token Checking
1. Launch the application
2. Select "Account Checker" from the tool selection
3. Enter Discord tokens (one per line or single token)
4. Click "Check Token" or "Check All Tokens"
5. Monitor results in the console logs
6. Optionally enable auto-removal of invalid tokens

### Account Generation
1. Select "Account Generator" from the main menu
2. Configure generation settings
3. Enter the number of accounts to generate
4. Enable rate limiting and notifications as needed
5. Click "Start Generation"
6. Monitor progress through application logs

## ⚠️ Important Notes

- This tool is for educational and authorized testing purposes only
- Ensure compliance with Discord's Terms of Service
- Use responsibly and ethically
- VPN usage recommended for better performance
- Keep your license key secure and private

## 🛠️ System Requirements

- **OS**: Windows 10/11 (recommended)
- **RAM**: 4GB minimum, 8GB recommended
- **Storage**: 100MB free space
- **Network**: Stable internet connection
- **Python**: 3.8+ with pip

## 📞 Support

For support and updates:
- Developer: @zyex1z
- Check application logs for troubleshooting
- Ensure all dependencies are properly installed

## 📄 License

This software is proprietary and requires a valid license key for operation. Unauthorized use is prohibited.

---

<div align="center">
  <strong>Developed by @zyex1z</strong><br>
  <em>Blur Toolz - Professional Discord Account Management</em>
</div>
