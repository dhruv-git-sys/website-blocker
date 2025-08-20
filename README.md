# Website Blocker

A simple Windows batch script to block distracting websites by modifying your system's `hosts` file.

## How It Works

This script adds entries to your Windows `hosts` file, redirecting popular distracting websites to your local machine (127.0.0.1), effectively blocking access to them.

## Blocked Websites

The following sites are blocked by default:
- x.com
- discord.com
- buzzfeed.com
- instagram.com
- netflix.com
- open.spotify.com
- reddit.com
- skype.com
- snapchat.com
- youtube.com
- troddit.com
- pinterest.com
- quora.com
- chess.com
- twitch.tv
- vimeo.com
- facebook.com
- mashable.com
- tagged.com

## Instructions

1. **Run as Administrator**

   You must run the script with administrator privileges to modify the `hosts` file.

   - Right-click `blocker.bat` and select **Run as administrator**.

2. **Effect**

   - The listed websites will be blocked on your computer.
   - To unblock, you must manually remove the added lines from `C:\Windows\System32\Drivers\etc\hosts`.

3. **To Unblock Sites**

   - Open Notepad as administrator.
   - Open the `hosts` file at `C:\Windows\System32\Drivers\etc\hosts`.
   - Remove the lines added by the script (those starting with `127.0.0.1` and the website name).
   - Save the file.

## Notes

- **Administrator rights are required** to run this script.
- You may need to restart your browser for changes to take effect.
- Use responsibly. Editing the `hosts` file can affect your network connectivity.
