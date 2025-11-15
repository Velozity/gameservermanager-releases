# Game Server Manager (GSM)

<div align="center">

A modern, cross-platform desktop application for managing game servers with ease.

![Version](https://img.shields.io/badge/version-1.0.5-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)

[Download Latest Release](https://github.com/velozity/gameservermanager-releases/releases/latest) | [Report Bug](https://github.com/velozity/game-server-manager/issues) | [Website](https://zacary.dev)

</div>

## 📋 Overview

Game Server Manager (GSM) is a powerful desktop application that simplifies the process of setting up, configuring, and managing dedicated game servers. Whether you're hosting a Minecraft server, Valheim server, or other popular game servers, GSM provides an intuitive interface to handle all aspects of server management from a single application.

## ✨ Features

- **🎮 Multi-Game Support** - Currently supports Minecraft, Valheim, and Rust with more games coming soon
- **🚀 Easy Server Creation** - Set up new game servers in minutes with guided setup wizards
- **⚙️ Configuration Management** - Edit server configurations through an intuitive UI
- **📊 Resource Monitoring** - Real-time CPU, memory, and network usage monitoring
- **🔄 Version Management** - Switch between different game server versions
- **📝 Log Viewing** - View and search through server logs in real-time
- **🌐 Port Mapping** - Automatic port configuration and conflict detection
- **⏰ Scheduled Tasks** - Automated server cleanup and maintenance
- **🎨 Modern UI** - Beautiful, dark-themed interface built with Tailwind CSS and Radix UI
- **💾 Database Storage** - Local SQLite database with Drizzle ORM for reliable data management
- **🔒 Secure** - Follows Electron security best practices with context isolation

## 🎯 Supported Games

| Game                   | Status       |
| ---------------------- | ------------ |
| Minecraft Java Edition | ✅ Supported |
| Valheim                | ✅ Supported |
| Rust                   | ✅ Supported |

## 📥 Installation

### Download

Download the latest version for your operating system from the [Releases Page](https://github.com/velozity/gameservermanager-releases/releases/latest):

- **Windows**: Download the `.exe` installer
- **macOS**: Download the `.dmg` file
- **Linux**: Download the `.AppImage` file

### System Requirements

- **OS**: Windows 10/11, macOS 10.13+, or modern Linux distribution
- **RAM**: 4GB minimum (8GB recommended)
- **Disk Space**: 500MB for the application, plus space for game servers

### First-Time Setup

1. Download and install GSM for your platform
2. Launch the application
3. Select a game from the server selection screen
4. Follow the guided setup wizard to create your first server
5. Start your server and enjoy!

## 📖 Usage Guide

### Creating a Server

1. Click "Create New Server" on the main screen
2. Select your game type (Minecraft, Valheim, etc.)
3. Configure server settings:
   - Server name
   - Port number (default ports are suggested)
   - Maximum players
   - Game version (if applicable)
4. Click "Create" to set up your server

### Managing Your Server

- **Start/Stop**: Use the control buttons to manage server state
- **View Logs**: Monitor server activity in real-time
- **Edit Config**: Modify server settings through the built-in editor
- **Resource Monitor**: Track CPU, RAM, and network usage

### Tips for Best Performance

- Allocate sufficient RAM based on your game and player count
- Keep ports open in your firewall/router for external access
- Regularly check logs for errors or warnings
- Use automatic cleanup to maintain optimal performance

## 🔧 Data Storage

GSM stores application data and server files in the following locations:

- **Windows**: `%APPDATA%\gamemanager-electron\`
- **macOS**: `~/Library/Application Support/gamemanager-electron/`
- **Linux**: `~/.config/gamemanager-electron/`

To backup your servers, simply copy this directory to a safe location.
Automated backups is in progress.

## ❓ Frequently Asked Questions

**Q: How do I create a new server?**  
A: Click the "Add Server" button on the main screen, select your game, configure the server settings (name, version, port), and click Create. The server will be automatically installed and ready to start.

**Q: Why won't my server start?**  
A: Common reasons include:

- The port is already in use
- The server files are corrupted
- Java/required dependencies are missing

Check the server logs for specific error messages and make sure no other servers are using the same port.

**Q: How do I/my friends connect to my server?**  
A: For local connections, use `localhost:PORT`. For external connections, you'll typically need to forward the port on your router and use your public IP address. This is taken care of for you if your router supports UPnP, otherwise you will need to set it up manually.

**Q: Where are my server files stored?**  
A: Server files are stored in your user data directory. You can quickly access them by clicking the "Open Folder" button on the server details page. Each server has its own isolated directory.

**Q: Is my server safe if I uninstall GSM?**  
A: Yes, your server will remain in the same folder it is in currently, even if you uninstall GSM.

**Q: How do I update my server version?**  
A: Stop the server, go to the server details page, and change the version in the settings. The new version will be downloaded automatically. Always backup your world/save files before updating.

**Q: What happens to deleted servers?**  
A: Deleted servers are moved to a trash/recycle area where they can be restored within 7 days. After that, they are permanently removed. You can also manually purge a server immediately from the trash.

**Q: How do I edit server configuration files?**  
A: Go to the server details page and click the "Config" tab. You can edit the main configuration file directly in the built-in editor. Changes are saved immediately. Make sure the server is stopped before making changes.

## 🐛 Support & Bug Reports

If you encounter any issues or have questions:

- **Bug Reports**: [Open an issue](https://github.com/velozity/game-server-manager/issues)
- **Feature Requests**: [Submit a request](https://github.com/velozity/game-server-manager/issues)
- **Email Support**: hey@zacary.dev

## 📄 Version History

See the [Releases Page](https://github.com/velozity/gameservermanager-releases/releases) for a complete version history and release notes.

## 📝 License

This project is licensed under the MIT License.

## 👤 About the Developer

**Zacary.dev**

- Website: [zacary.dev](https://zacary.dev)
- GitHub: [@Velozity](https://github.com/Velozity)
- Email: hey@zacary.dev

---

<div align="center">

**[Download Latest Release](https://github.com/velozity/gameservermanager-releases/releases/latest)**

Made with ❤️ by zacary.dev

</div>
