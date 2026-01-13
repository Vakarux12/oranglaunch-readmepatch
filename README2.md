
<h1 align="center">Orange Launcher</h1>

<p align="center">
  A modular, modern, and highly customizable Minecraft launcher powered by a lightweight Python backend.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/452fc8c2-7aea-4cf4-877f-da04ce869d63" alt="Orange Launcher" width="720">
</p>

---

## Installation (Arch Linux)

Install with **yay**:

`yay -S oranglauncher-bin`

> [!NOTE] Windows support is coming later. The current Python build on Windows is still buggy and uncomfortable to use. A major rewrite is planned - Linux will keep receiving updates in the meantime.




---

About

Orange Launcher is built to deliver a modular, modern, and highly customizable Minecraft experience. It uses a built-in Python backend to stay lightweight, fast, and fully scriptable - while keeping the UI clean and easy to navigate.


---

Features

Accounts

Microsoft (Mojang)

Microsoft login is handled through a local (localhost) authentication flow embedded in a Qt6 web view.
If embedding fails, the launcher opens your browser to complete the same localhost flow.

The launcher receives tokens directly from Microsoft (not from the developer).

Tokens are used to confirm you’re the legitimate account owner.


Offline (Cracked)

Offline accounts let you enter a username and play singleplayer or on offline/cracked servers.

Offline accounts don’t include official skins.

You are responsible for using this feature legally. The developer is not affiliated with Mojang/Microsoft/Xbox.



---

News Hub

A dynamic news page that fetches and displays updates, announcements, and community info.

Auto-refreshing content

Clean, scroll-friendly layout



---

Modding Panel

A dedicated modding tab with tools for managing mods more easily:

Simple mod installation & management

Version-aware compatibility handling

Automatic folder structuring for cleaner organization

Modpack support: .mrpack (Modrinth)



---

Profiles System

Create and switch between multiple profiles. Each profile can have its own:

Game version

Profile name

Loader (Fabric/Forge/etc.)

Loader version

RAM allocation

And more



---

Resource Packs & Shaders

A unified tab for visuals:

Enable/disable and reorder resource packs

Toggle shaders seamlessly

Add/remove shaderpacks and resourcepacks



---

Settings

A settings page for launcher customization, including:

General launcher settings

Accounts settings

Additional options

About page



---

Language Support

The UI supports multiple languages (including community translations).
Switching languages reloads the interface.


---

Built-in Python Engine

Core launcher logic runs on Python, enabling:

Easy scripting and feature expansion

Faster bug fixing and iteration

Cross-platform potential (rewrite in progress for Windows)

Launcher modding / extensibility



---

For Developers

Check the Wiki for tutorials, examples, and build instructions:

Architecture overview

Adding features

Building from source

Creating your own modules