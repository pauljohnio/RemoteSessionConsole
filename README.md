# RemoteSessionConsole

A local dark-mode webpage for online training sessions in Teams, Zoom, or similar screen-sharing tools.
Provides timers, messages to help manage an online course session.
Includes optional AirSketch Pro support to provide a quick whiteboard with iPad support without needing new browser tabs.

Live URL after the repository is renamed:

https://pauljohnio.github.io/RemoteSessionConsole/

## Use It

Open `index.html` directly in your browser. You can keep it on your Desktop, copy it to another machine, or run it from a USB drive.

Make the browser window the same size as the desktop area you share. Use **Fullscreen** if you want it to cover everything.

## What It Does

- Shows a large clock and date.
- Shows the app name and version on the config screen.
- Lets you configure the presenter name, email, and optional link shown on the display.
- Shows a large session message such as "Starting soon", "On a break", "One moment", or "Micro break".
- Keeps a **Custom** quick status based on the last status/message you typed.
- Starts break timers from quick presets or a specific return time.
- Shows a **Session End** thank-you message with optional email, URL, and follow-up text.
- Uses **Display View** to hide controls while sharing.
- Shows a small **Controls** button in clean view so you can get back.
- Uses shortcuts: `Esc` or `C` for Config, `D` for Display View, `B` for Blank, `H` for One moment, and `W` for Whiteboard.
- Opens a clean whiteboard display from the **Whiteboard** button, with a **One moment** emergency button.

## Tips

- Set your Zoom or Teams share to this browser window, not the whole desktop, when possible.
- If you share the whole desktop, put this window full-screen over your icons before sharing.
- When the whiteboard gives you a new IP address, click **Whiteboard**, choose **Settings** if the board is already loaded, paste the new address, and choose **Load whiteboard**. The address is saved for next time.
