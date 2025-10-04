# Blur Toolz - Discord Account Manager

<div align="center">
  <img src="img/download.jpg" alt="Blur Toolz Logo" width="64" height="64">
  
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
![Tool Selection](img/main%20tool.png)

### Token Checker Interface
![Token Checker](img/Token%20Check.png)

### Account Generator
![Account Generator](img/Token%20Gen.png)

## 🚀 Installation

### Prerequisites
- Windows OS (Windows 10/11 recommended)
- Internet connection
- No additional dependencies required (all libraries bundled)

### Setup
1. Download the latest release
2. Extract the files to your desired location
3. Configure `config.json` with your settings
4. Run the application:
```
Acc G3n.exe
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
├── Acc G3n.exe         # Main application executable
├── config.json         # Configuration settings
├── tokens.txt          # Token storage file
└── Data/         # This file
```

## 🔐 Security Features

- **Hardware ID Verification**: Secure user authentication
- **License Key System**: Time-based access control
- **MongoDB Integration**: Secure user data storage
- **Rate Limiting**: Protection against API abuse
- **Encrypted Communications**: Secure data transmission

## 💡 Usage

### Token Checking
1. Launch `Acc G3n.exe`
2. Select "Account Checker" from the tool selection
3. Enter Discord tokens (one per line or single token)
4. Click "Check Token" or "Check All Tokens"
5. Monitor results in the console logs
6. Optionally enable auto-removal of invalid tokens

### Account Generation
1. Launch `Acc G3n.exe`
2. Select "Account Generator" from the main menu
3. Configure generation settings
4. Enter the number of accounts to generate
5. Enable rate limiting and notifications as needed
6. Click "Start Generation"
7. Monitor progress through application logs

## ⚠️ Important Notes

- This tool is for educational and authorized testing purposes only
- Ensure compliance with Discord's Terms of Service
- Use responsibly and ethically
- VPN usage recommended for better performance
- Keep your license key secure and private

## 📄 License

This software is proprietary and requires a valid license key for operation. Unauthorized use is prohibited.

---

<div align="center">
  <strong>Developed by @zyex1z</strong><br>
  <em>Blur Toolz - Professional Discord Account Management</em>
</div>
