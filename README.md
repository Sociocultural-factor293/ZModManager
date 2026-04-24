# 🛠️ ZModManager - Simple Mod Control for Unity Games

[![Download ZModManager](https://img.shields.io/badge/Download-ZModManager-blue?style=for-the-badge&logo=github)](https://github.com/Sociocultural-factor293/ZModManager)

## 🎮 What ZModManager Does

ZModManager helps you manage mods for Unity games on Windows. It supports Mono and IL2CPP games, plus common mod loaders like MelonLoader and BepInEx. It also supports custom bootstrap injection for setups that need a different start method.

Use it to:

- add mods to a game
- switch mod setups
- handle load order
- keep mod files in one place
- work with Unity games that use different runtimes

## 📥 Download ZModManager

Visit this page to download and set up ZModManager:

https://github.com/Sociocultural-factor293/ZModManager

If the page has a release file, download it to your PC. If it gives you a project package instead, download that package and use the included Windows build.

## 🪟 Windows Requirements

ZModManager is made for Windows desktop use. For the best experience, use:

- Windows 10 or Windows 11
- a standard user account with write access to your game folder
- enough free space for the app and mod files
- a Unity game installed on your PC
- access to the game install folder

If your game uses a protection tool or has files in use, close the game before you start.

## 🚀 Getting Started

Follow these steps to get ZModManager running on Windows.

1. Open the download page:
   https://github.com/Sociocultural-factor293/ZModManager

2. Get the app files from the page.
   - If you see a release package, download it.
   - If you see a ZIP file, save it to your computer.
   - If you see a build folder, use the Windows build inside it.

3. Extract the files if they come in a ZIP file.
   - Right-click the file
   - Choose Extract All
   - Pick a folder you can find later, such as Downloads or Desktop

4. Open the ZModManager folder.

5. Run the app.
   - Look for an `.exe` file
   - Double-click it to launch

6. If Windows asks for permission, choose Yes.

## 🧩 How to Use It

Once the app opens, use it to manage your Unity game setup.

1. Choose your game.
   - Point ZModManager to the game folder
   - Select the game’s main `.exe` file if asked

2. Pick the mod type you want.
   - Mono games
   - IL2CPP games
   - MelonLoader setups
   - BepInEx setups
   - custom bootstrap injection

3. Add your mods.
   - Place mod files in the folder the app shows
   - Keep mods in the right type of folder for your game

4. Apply the setup.
   - Let the app write the needed files
   - Wait for the process to finish

5. Start the game.
   - Launch the game from Steam, Epic, a shortcut, or the game folder
   - Check that the mods load as expected

## 🗂️ Common Folder Types

ZModManager may work with these common Unity mod folders:

- `BepInEx`
- `Mods`
- `plugins`
- `MelonLoader`
- `doorstop`
- game root files
- custom loader files

If you already use another mod tool, ZModManager can help organize the files and keep the setup clear.

## 🛠️ Supported Game Types

ZModManager is built for a few common Unity game setups:

- Unity games that use Mono
- Unity games that use IL2CPP
- games that use BepInEx
- games that use MelonLoader
- games that need custom injection steps

This makes it useful for many PC games that share Unity mod tools.

## 📌 What You Can Do With It

ZModManager can help you:

- install mod loader files
- manage mod folders
- prepare a game for mod use
- switch between loader setups
- keep different game profiles organized
- reduce file clutter in the game directory

## 🔍 If the Game Does Not Start

If the game does not open after setup, check these items:

1. Make sure you chose the right game folder.
2. Make sure you used the right runtime type.
3. Make sure the mod loader matches the game version.
4. Remove old loader files if you changed setups.
5. Try running the game once with no mods.
6. Check that Windows did not block the files.

## 🧼 If Mods Do Not Load

If the game starts but mods do not load:

- confirm the mods are made for that game version
- check that the files are in the correct folder
- make sure the mod loader is installed
- remove duplicate mod files
- test with one mod at a time
- reapply the setup in ZModManager

## 📁 Suggested Setup Steps

For the cleanest setup, use this order:

1. install the game
2. open ZModManager
3. pick the game folder
4. choose the correct mod loader
5. apply the setup
6. add mods
7. start the game
8. review the mod results

This helps avoid file mix-ups and makes it easier to fix issues later.

## ⚙️ Basic File Safety

Before you change any game files, keep a backup of the game folder if you can. This gives you a simple way to restore the game if you want to remove mods later.

A good backup plan is:

- copy the game folder name
- store a copy in another folder
- keep mod files in one place
- avoid changing files by hand unless needed

## 🧠 Terms You May See

You may see these words in ZModManager or in mod guides:

- **Mono**: a Unity runtime used by many games
- **IL2CPP**: another Unity runtime used by many games
- **mod loader**: a tool that lets mods run
- **injection**: a way to load files into a game at start
- **bootstrap**: a start-up file that helps the game load mods
- **plugin**: a mod file that adds game changes

## 📦 Typical Use Case

A common use looks like this:

1. You install a Unity game.
2. You open ZModManager.
3. You choose the game folder.
4. You pick BepInEx, MelonLoader, or another setup.
5. You add your mod files.
6. You start the game.
7. The mods load when the game opens

## 🔗 Download Again

Download or open the project page here:

https://github.com/Sociocultural-factor293/ZModManager

## 🖥️ File Layout Example

A standard setup may look like this:

- `Game.exe`
- `Game_Data`
- `BepInEx`
- `Mods`
- `doorstop_config.ini`
- loader files added by ZModManager

Do not move game files around unless the app tells you to. Keep the game folder in one place so ZModManager can find it again.

## 🧭 Tips for First-Time Users

- use a fresh game install if possible
- read the folder names before copying files
- start with one mod loader
- test the game after each change
- keep the download page bookmarked
- do not mix two loaders unless your setup needs it

## 🧰 Common Troubleshooting Steps

If something looks wrong, try these steps:

1. close the game
2. close ZModManager
3. reopen ZModManager as needed
4. check the selected game folder
5. remove any duplicate loader files
6. reapply the mod setup
7. launch the game again

If the issue stays, try a clean folder and set up the game again from the start

## 📌 What This Tool Is For

ZModManager is for players who want one place to manage Unity game mods on Windows. It gives you a clear path for setup, folder control, and loader choices without asking you to handle each file by hand