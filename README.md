# Cursor Reset Tool
Created by Riad developer

## ⚠️ Note
This tool is only available for Windows users.

## 📝 Description
A PowerShell script to reset Cursor IDE machine identifiers. This tool helps you reset your Cursor installation without running any external applications.

## 🚀 Prerequisites
- Windows Operating System
- PowerShell
- Administrator privileges

## 📋 Instructions

1. **Preparation**
   - Sign out of Cursor on both IDE and browser
   - Close the Cursor application completely
   - Download and install the [latest version of Cursor](https://www.cursor.com/downloads)
   - Launch Cursor once and close it without signing in

2. **Running the Script**
   ```powershell
   cd $env:USERPROFILE\Downloads
   powershell -ExecutionPolicy Bypass -File .\reset_cursor_windows_by_Riad_developer.ps1
   ```

3. **After Reset**
   - Open Cursor IDE and proceed with sign up
   - Create a temporary email at [Temp Mail](https://mailticking.com/)
   - Complete the registration process

## ⚙️ What the Script Does
- Generates new unique identifiers
- Updates machineId file
- Updates storage.json
- Updates SQLite database
- Updates Windows Registry MachineGuid
- Creates backups of modified files

## 🔄 Backup
The script automatically creates backups of all modified files. If you need to revert the changes, you can find backup files with the `.backup` extension.

## ⚠️ Important Notes
- Always run PowerShell as Administrator
- Make sure Cursor is completely closed before running the script
- If any stage fails, switch to the manual method
- All your previous Cursor settings will be reset

## 🤝 Support
If you encounter any issues, please ensure you've followed all steps correctly and have the necessary permissions.

## 📜 License
This tool is provided as-is, without any warranty. Use at your own risk. 