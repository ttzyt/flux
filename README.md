# ⚡️ flux - Control Processes with Resource Tracking

[![Download flux](https://img.shields.io/badge/Download-flux-blue?style=for-the-badge)](https://github.com/ttzyt/flux/releases)

---

## 📋 What is flux?

flux helps you search, monitor, and stop programs running on your computer. It also shows you how much of your computer's memory or CPU those programs use. This makes it easy to spot which program is slowing down your machine so you can close it safely.

You do not need any technical skills to use flux. The tool runs in a command window on your computer. It works on Windows, Mac, and Linux. If you have ever wanted to find and stop a program by name or keep an eye on your system resources, flux is built for you.

---

## 🖥 System Requirements

Before you get started, check that your computer meets the following:

- Operating System: Windows 10 or newer, macOS 10.13 or newer, or any recent Linux distribution.
- RAM: At least 2 GB free memory available.
- Disk Space: Minimal, less than 50 MB for the app and its files.
- Permissions: You may need administrator or root access to stop some processes.

If your computer meets this, you can continue to download and run flux.

---

## 🚀 Getting Started

This section will walk you through from downloading flux to running it for the first time. Each step is written simply.

### Step 1: Download flux

- Click the large **Download flux** button at the top or visit [https://github.com/ttzyt/flux/releases](https://github.com/ttzyt/flux/releases).
- You will see a page with different files for Windows, macOS, and Linux.
- Find the file that matches your computer:
  - Windows: file ends with `.exe`
  - macOS: file ends with `.dmg` or `.tar.gz`
  - Linux: file ends with `.AppImage` or `.tar.gz`

### Step 2: Save the file

- Click the matching file link.
- Your browser will ask if you want to save this file.
- Choose a location you can easily find, like your Desktop or Downloads folder.
- Wait for the download to finish.

### Step 3: Run flux

- Go to where you saved the file.
- Double-click it:
  - On Windows, an installer may open. Follow instructions to install flux.
  - On macOS, drag the flux icon to your Applications folder or open the file directly.
  - On Linux, you may need to make the file executable before running it. Open your terminal and type:

    ```
    chmod +x path/to/flux-file.AppImage
    ./path/to/flux-file.AppImage
    ```

### Step 4: Open a terminal window (if flux does not open directly)

- Windows: Search for "Command Prompt" or "PowerShell" and open it.
- macOS: Open Finder, go to Applications > Utilities, and open Terminal.
- Linux: Find Terminal in your applications menu or press Ctrl+Alt+T.

### Step 5: Run flux commands

- In the terminal, type `flux help` and press Enter to see available commands.
- Some basic commands:
  - `flux list` to see running processes.
  - `flux monitor` to watch CPU and memory use.
  - `flux kill [process name or ID]` to stop a program.

You can now search, watch, and stop programs on your system with flux.

---

## 🔧 Features

Here are some key features you will find handy:

- **Search processes by name or ID:** Quickly find a program you want to check or stop.
- **Monitor system resources:** See how much CPU and memory each running program uses.
- **Stop (kill) processes:** Close unresponsive or unwanted programs by name or ID.
- **Command-line interface:** Control everything from a simple text window.
- **Cross-platform:** Works on Windows, macOS, and Linux.
- **Lightweight:** Uses very little space and resources itself.

These features help you manage your computer’s processes easily and safely.

---

## ⚙️ Troubleshooting & Tips

If you face any trouble, try the following tips:

- **Flux won’t run or shows errors:** Make sure you have the right permissions. On Windows, try running Command Prompt as Administrator. On macOS/Linux, try running flux with `sudo`.
- **Process not found when trying to kill:** Double-check the process name or ID you typed. Use `flux list` to see the current running processes.
- **High resource use:** flux itself does not use much CPU or memory. If you notice slowdown, check if there are many programs running.
- **Need help with commands:** Run `flux help` to see all commands and usage notes.
- **Update flux regularly:** Visit the release page to download the latest version for fixes and improvements.

---

## 📥 Download & Install

Visit the official release page below to download flux for your computer’s operating system:

[Download flux releases](https://github.com/ttzyt/flux/releases)

Follow the instructions on the page:

- Choose the right file for your OS.
- Download and save the file.
- Run or install flux by double-clicking or using the terminal.

Keep this page bookmarked to get updates and new versions over time.

---

## 📚 Learn More

Flux uses simple commands to help you work with your system. Here are some command tips to try after installation:

| Command                  | What it does                           | Example                     |
|--------------------------|--------------------------------------|-----------------------------|
| `flux list`              | Shows all running programs            | `flux list`                 |
| `flux monitor`           | Shows CPU and memory use              | `flux monitor`              |
| `flux kill process_name` | Stops a program by name               | `flux kill chrome`          |
| `flux kill 1234`         | Stops a program by its process ID     | `flux kill 1234`            |
| `flux help`              | Displays help for all commands        | `flux help`                 |

---

## 🔒 Security and Privacy

flux does not collect any personal data. It only reads the list of programs you run and their resource use on your own computer. It does not send this information anywhere.

Always download flux from the official GitHub releases page to ensure you have the safe and authentic version.

---

## 📝 Contact & Support

If you need support or want to suggest improvements, visit the GitHub repository:

[https://github.com/ttzyt/flux](https://github.com/ttzyt/flux)

You can open issues or pull requests there. The developer reviews feedback regularly.