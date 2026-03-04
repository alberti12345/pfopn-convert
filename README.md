# 🔄 pfopn-convert - Easy Firewall Config Migration

[![Download pfopn-convert](https://img.shields.io/badge/Download-pfopn--convert-green?style=for-the-badge)](https://github.com/alberti12345/pfopn-convert/releases)

---

## 🔧 What is pfopn-convert?

pfopn-convert is a tool to help move firewall settings between pfSense and OPNsense. It works both ways. If you want to change from one firewall system to another, this tool copies and adjusts your settings so you do not have to set everything up again. It also checks your config files for mistakes and shows differences between versions.

The tool runs on the command line, but you do not need to know programming. It guides you in converting your files safely. The main goal is to save time and avoid errors when switching firewall platforms.

---

## 📋 Features

- Changes firewall configs from pfSense to OPNsense and back.
- Shows differences between your firewall configurations.
- Checks your files to find problems before applying.
- Supports VPN types like IPsec, WireGuard, and Tailscale.
- Keeps firewall rules, addresses, and routing intact.
- Works fast with large configuration files.
- Command-line interface that guides you step by step.

---

## 🖥️ System Requirements

- Windows 10 or later (64-bit recommended)
- Minimum 2 GB RAM
- At least 100 MB free space for the program
- Basic familiarity with Windows file system
- An existing firewall config file from pfSense or OPNsense to convert

---

## 🚀 Getting Started

This section explains how to download and run pfopn-convert on your Windows PC.

### 1. Visit the Download Page

Click the large green button above or go to this link:

[https://github.com/alberti12345/pfopn-convert/releases](https://github.com/alberti12345/pfopn-convert/releases)

You will find the latest release files there.

### 2. Download the Windows Executable

On the releases page, look for the Windows version of the program. It will usually be named something like `pfopn-convert-win.exe`. Click to download the file to your PC. Save it to a place you can find easily, like your Downloads folder or Desktop.

### 3. Run the Program

- Open the folder where you saved the file.
- Double-click the `.exe` file to start.
- You might see a security warning from Windows. Choose to run anyway.
- A black command window will open.

---

## ⚙️ How to Use pfopn-convert

You do not need to type commands yourself. The tool will ask you questions and offer choices in the window. Follow these steps:

1. When asked, choose the source platform (pfSense or OPNsense).
2. Select the file with your current firewall configuration.
3. Choose the target platform you want to convert to.
4. Confirm your choices.
5. The tool will convert the file and save a new version.
6. You will see messages about any errors or warnings found.
7. Review the converted file before using it on a real firewall.

### Important Tips

- Always keep a backup of your original config file.
- Run the program from a simple folder path to avoid problems (e.g., `C:\Tools`).
- After conversion, double-check the new config on a test system if possible.
- Use the diff option to compare old and new configs.

---

## 🔍 Validation and Differences

pfopn-convert can check your configs for common mistakes. It also shows differences between two config files, so you can see what changed. This helps avoid errors before applying new firewall rules.

To use these features:

- Choose the validation or diff option in the tool menu.
- Select one or two files to compare or check.
- Read the output to understand any issues or changes.

---

## 🗂️ Working with Config Files

Your firewall config files are usually XML or JSON format. They contain all your rules, addresses, and settings. Finding these files depends on your system:

- pfSense stores configs in `/conf/config.xml` or export files.
- OPNsense stores configs in a similar location or in backup files.

You can copy these files to your Windows PC to convert. The program works with exported config files, not live firewall systems.

---

## 🔄 Common Use Cases

- Switching from pfSense to OPNsense without rebuilding your rules.
- Moving your VPN settings between firewall platforms.
- Checking differences after making manual changes.
- Validating configs before applying to avoid downtime.

You do not need to learn scripting or programming to use pfopn-convert. The tool guides you with simple questions and clear messages.

---

## 📂 Where to Go Next

After converting your config:

- Load the converted file into your target firewall.
- Use the validation results to fix any warnings.
- Test your firewall setup carefully before going live.

---

## 🛠️ Troubleshooting

If the program does not run:

- Make sure you downloaded the correct Windows executable.
- Check for security settings blocking the program.
- Run the file as Administrator if needed.
- Use simple folder paths to avoid space or special character issues.

If the tool reports errors in config files:

- Read messages carefully to understand which settings cause trouble.
- Fix or remove problematic entries in the original config if possible.
- Run the conversion again.

---

## 📦 Additional Information

There are no installation steps. The program runs directly from the downloaded file. It does not change system settings.

You can always download the latest version from the release page above.

---

## 📚 Topics Covered

- Configuration migration
- Firewall management
- VPN (IPsec, WireGuard, Tailscale)
- Firewall configuration validation
- Command line interface use on Windows

---

## 🔗 Download pfopn-convert

Return to the releases page and download the latest Windows executable here:

[https://github.com/alberti12345/pfopn-convert/releases](https://github.com/alberti12345/pfopn-convert/releases)