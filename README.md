<p align="center">
  <img src="assets/logo.png" width="96" alt="">
</p>

<h1 align="center">Atlas Pilot</h1>

<p align="center">The IDE for Roblox Studio. Write your scripts in a real editor, sync them with Studio both ways, and let an AI agent build, fix and playtest with you.</p>

<p align="center">
  <a href="https://github.com/KiddyDevOfficial/atlas-pilot-releases/releases/download/setup/Atlas-Pilot-Setup.exe"><img src="https://img.shields.io/badge/Download_for_Windows-Atlas--Pilot--Setup.exe-0165fd?style=for-the-badge&logo=windows11&logoColor=white" alt="Download Atlas Pilot for Windows"></a>
  <a href="https://github.com/KiddyDevOfficial/atlas-pilot-releases/releases/download/setup/Atlas-Pilot-Mac.dmg"><img src="https://img.shields.io/badge/Download_for_Mac-Atlas--Pilot--Mac.dmg-111111?style=for-the-badge&logo=apple&logoColor=white" alt="Download Atlas Pilot for Mac"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/KiddyDevOfficial/atlas-pilot-releases?label=latest&style=flat-square&color=555" alt="Latest version">
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-555?style=flat-square" alt="Windows 10 or 11">
  <img src="https://img.shields.io/badge/macOS-11%2B%20(Apple%20Silicon%20%26%20Intel)-555?style=flat-square" alt="macOS 11 or newer, Apple Silicon and Intel">
</p>

---

## Install on Windows

1. **[Download Atlas-Pilot-Setup.exe](https://github.com/KiddyDevOfficial/atlas-pilot-releases/releases/download/setup/Atlas-Pilot-Setup.exe)**. That's the only file you need.
2. Run it. Windows may say *"Windows protected your PC"*, because Atlas Pilot isn't code-signed yet. Click **More info**, then **Run anyway**.
3. Atlas Pilot opens when setup finishes, and you'll find it on your desktop and in the Start menu. The welcome guide connects your AI account, installs the Atlas Studio plugin and sets up your project.

## Install on Mac

1. **[Download Atlas-Pilot-Mac.dmg](https://github.com/KiddyDevOfficial/atlas-pilot-releases/releases/download/setup/Atlas-Pilot-Mac.dmg)**. One app for Apple Silicon and Intel Macs.
2. Open it and drag **Atlas Pilot** into **Applications**.
3. Open Atlas Pilot from Applications. Because it isn't notarized by Apple yet, macOS says it can't check the app: click **Done**. Then open **System Settings**, **Privacy & Security**, scroll down and click **Open Anyway** next to Atlas Pilot. You only do this once.

   Prefer Terminal? This does the same in one step:

   ```
   xattr -dr com.apple.quarantine "/Applications/Atlas Pilot.app"
   ```

4. The welcome guide connects your AI account, installs the Atlas Studio plugin and sets up your project.

## Updates

You never download Atlas Pilot again, on Windows or Mac. When there's a new version, an **Update** button appears in the title bar. Click it, then **Restart to update**, and you're on the new version. Your spaces and settings stay.

To check by hand: **Help**, **Check for Updates**.

## What it does

- **An IDE for Roblox scripts.** Tabs, breadcrumbs, Quick Open, find in scripts, problems and Luau completions, laid out like the editors you already know.
- **An AI agent that works in your place.** Use your Claude, ChatGPT or Gemini account, pick the model and how hard it thinks. It reads and writes your scripts, builds UI and models, runs playtests, and every change it makes can be kept or reverted.
- **Two-way Studio sync.** The Atlas plugin keeps the scripts in Studio and the files in your project folder in sync, both ways, with no other sync tool needed.
- **A built-in terminal** for git, Rojo, or anything else you run.
- **Properties and UI preview.** Inspect and edit instance properties and preview your ScreenGuis without leaving the app.

## What you need

- Windows 10 or 11, or macOS 11 or newer (Apple Silicon or Intel)
- Roblox Studio
- A Claude, ChatGPT or Gemini account, or an API key, for the agent

## Which file do I download?

Only **Atlas-Pilot-Setup.exe** (Windows) or **Atlas-Pilot-Mac.dmg** (Mac), from the buttons above. The other files on the [Releases](https://github.com/KiddyDevOfficial/atlas-pilot-releases/releases) page (`latest.json`, the versioned files and their `.sig`) are what Atlas Pilot downloads by itself when it updates. You can ignore them.

[All versions](https://github.com/KiddyDevOfficial/atlas-pilot-releases/releases)
