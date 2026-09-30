# Flipper

Flipper sets up Flipper's Vencord plugin pack on a Windows PC and keeps it working when Discord updates. It comes with an installer, a dashboard, and a background keeper. And Flipper himself, a small glowing dolphin, lives in the window.

## Download

**[Download Flipper for Windows](https://github.com/AlteredCloud/flipper/releases/latest/download/Flipper-Setup.exe)** (always the newest version)

## Install

1. Double-click `Flipper-Setup-x.y.z.exe`.
2. Look over the Plugins, Suggestions, Automation and Appearance pages, then press **Install**.

The app isn't code-signed yet, so Windows may say "Windows protected your PC". Press **More info**, then **Run anyway**.

No admin rights are needed. If Git, Node.js or pnpm are missing, Flipper puts private copies in `%USERPROFILE%\Flipper\tools` and leaves your system PATH alone.

**Never used Vencord?** You don't need to set it up first. Flipper installs Vencord for you, about 3 to 5 minutes.

**Needs:** Windows 10 or 11 and the Discord desktop app.

## What's in the pack

| Plugin | What it does |
|---|---|
| Flipper | Checks inside Discord that every plugin still works, and repairs things after Discord updates |
| ChatExporter | Right-click a message, then Export from here |
| Dictate | Local voice typing through a speech server on your own PC |
| SendLater | Undo send, or schedule messages for later |
| Trails | A cursor particle trail |

## Updates

Flipper checks this repository for a new release once a day. It verifies the file's sha256 before using it. By default it asks first; you can have it install updates by itself, or turn the check off, on the Automation page.

## Uninstall

Settings, Apps, Installed apps, Flipper, Uninstall.

## If something goes wrong

Open Flipper, go to Activity and press **Save a report**. It puts a zip of logs and basic system facts on your Desktop. It never includes tokens or passwords.

Upgrading from Vencord Companion? Just run the Flipper Setup. It moves everything over and keeps your settings.
