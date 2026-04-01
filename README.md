Audiobook Controller

A local Discord audiobook player with a GUI for controlling playback, jump positions, and viewing cover art. Works on Linux and Windows.

Features
Play, pause, and resume audio in Discord voice channels
Jump ±1 minute or set a custom timestamp
Displays audiobook cover art
Simple desktop GUI controller
Automatic dependency setup via launch scripts
Cross-platform (Linux + Windows)

Dependencies install automatically on first run.

Linux

Right click "run.sh" run as program

or

chmod +x run.sh
./run.sh

Windows

Double-click:

run.bat

or run:

.\run.bat

The launcher will:

Create a virtual environment if missing
Install required Python packages
Configure runtime paths
Start the application

Discord Bot Setup

1. Create the Bot
Open the Discord Developer Portal
https://discord.com/developers/applications
Click New Application
Go to Bot → Add Bot
Copy the Bot Token

2. Add Token to Project

Copy paste token to app while open hit enter key

3. Generate the Invite Link

Inside the Developer Portal:

Open your application
Go to OAuth2 → URL Generator
Select Scopes

✅ bot

Select Bot Permissions

Enable:

✅ View Channels
✅ Read Message History
✅ Connect
✅ Speak
✅ Use Voice Activity
Copy the generated URL at the bottom
Open it in your browser
Choose your server and authorize

The bot will now be able to join voice channels and play audio.

Audio Requirements
ffmpeg must be available:
Installed globally or
Included inside the project folder (Windows supported)

Supported formats:

.m4b
.mp3
.m4a

License

MIT License © 2026 Samuel Darrah

You are free to:

Use
Modify
Redistribute
Reupload modified versions

Please retain attribution to the original author.
