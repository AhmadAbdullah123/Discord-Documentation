# Discord

## Table of Contents
1. [Overview](#overview)
2. [Key Features](#key-features)
3. [Installation Guide](#Installation-Guide)
    - [Windows Installation](#Windows)
    - [macOS Installation](#macOS)
    - [Linux Installation](#Linux)
4. [User Guide](#User-Guide)
    - [Creating a Server](#Creating-a-Server)
    - [Joining a Server](#Joining-a-Server)
    - [Collaboration](#Collaboration)
    - [Reporting](#Reporting)
5. [Troubleshooting](#Troubleshooting)
7. [Advanced Usage](#Advanced-Usage)
    - [Integration](#Integrations)

---
## Overview
[**Discord**](https://discord.com/) is a powerful multipurpose communication tool
was designed mainly for communities such as gaming, school club, study group, artists and createors. Discord allows users to create or join servers to communicate with each other. Discord provide a various features such as voice channels, text chat, and screen sharing. 

---

## Key Features

- **Create a server**: Create a server and choose if you want it to be public or private.
- **Join a server**: This feature allow users to join a public server or private server by invitation. 
- **Voice Channels**: Join voice channels to communicate in real time with your team. 🔊
- **Text Chat**: Sending messages withing a server.
- **Screen Sharing**: Share your screen to present during meetings. 🖥️
- **Role Management**: This function is used by owners to manage members with custom roles and permissions.

---

## Installation Guide

### Windows

1. Visit Discord official website https://discord.com/download
2. Tap on the **Download for Windows** button to download the app.
![text](https://support.discord.com/hc/article_attachments/18368153374359)
3. Follow your browser's prompts to save and open the **DiscordSetup.exe** to start the installation process.
4. Once installed, you can then open the Discord app and register an account or log into an existing account.

### macOS

1. Visit Discord official website https://discord.com/download
2. Tap on the **Download for Mac** button to download the app.
![text](https://support.discord.com/hc/article_attachments/18368200112279)
4. Open the Discord.dmg file.
5. Drag the Discord logo and drop it over the Applications folder in the pop-up window.

### Linux

1. Visit Discord official website https://discord.com/download
2.  Tap on the **Download for Linux** button to download the app.
![text](https://support.discord.com/hc/article_attachments/18368200137879)
3. For manual installation on a Debian based distribution you can use the following commands
    ```bash
   -   cd ~ /Downloads
    ```
    ```bash
     -   sudo dpkg -i package.deb or sudo apt install ./package.deb
	```
4. Now that the app is installed, you can register a Discord account or log into an existing one.
---

## User Guide

### Creating a Server

To create a new server in **Discord**, follow these steps:

1. Open the Discord app.
2. Click on the **+** button to create a new server.
3. Choose a Template or Create My Own
4. Name your server.
5. Public or Private server
6. Invite friends or team members to your server.

### Joining a server

To join a server in **Discord**, follow these steps:

1. Open the Discord app.
2. Click on the **+** button.
3. Choose "Join a server" 
4. Enter the invitation URL

### Collaboration

Discord provides various collaboration tools for users.
Comparison between the different options they provide:

| Options  | Description                             | Tools Available             |
|-----------------------|-----------------------------------------|-----------------------------|
| **Shared Channels**    | Share text and voice channels with others | Invite link, permissions     |
| **Role Assignments**   | Assign roles and permissions to members | Role management, permissions |
| **Communication Tools**| Communicate by either voice, video, or text   | Voice channels, screen share |

### Reporting

We can use Discord Bot or external tools to generate report for a specific server at a specific time. 
Example of server report using JSON format: 


```json
	   {
	  "server_name": "Call of Duty: Modern Warfer 3",
	  "total_members": 1560,
	  "active_members": 461,
	  "messages_sent": 3126,
	  "voice_hours": 913
	}
```

## Troubleshooting 

Here are some common issues users might encounter while using Discord and how to resolve them:

- **Discord won’t connect**:  
    Ensure that you're connected to the internet,
    if the problem still there, check the **Discord** server status.

- **Audio issues**:  
   If you're encountring an Audio issue you can check the voice settings in the application, or the system settings.
   If the proble is still there then update the input/output drivers.


## Advanced Usage

### Integrations

Discord integrates with several external applications to enhance functionality and collaboration. Here’s a list of some available integrations:

| Application       | Description                                    | Link                            |
|-------------------|------------------------------------------------|---------------------------------|
| **YouTube**       | Watch and share videos directly in chat         | [YouTube][youtube-link]         |
| **Twitch**        | Stream live content and notify your Discord users | [Twitch][twitch-link]           |
| **GitHub**        | Get notifications for repository updates       | [GitHub][github-link]           |

[youtube-link]: https://youtube.com "YouTube"
[twitch-link]: https://twitch.tv "Twitch"
[github-link]: https://github.com "GitHub"
