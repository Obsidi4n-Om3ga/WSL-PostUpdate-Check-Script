# WSL-PostUpdate-Check-Script
✅ PowerShell script to check WSL status after Windows updates or auto reboots. Lightweight diagnostic tool for developers using WSL.
# 🐧 WSL Post-Update Check Script (PowerShell)

This PowerShell script is designed to verify the status of the **Windows Subsystem for Linux (WSL)** after a system update or automatic reboot. It's a handy diagnostic tool for ensuring WSL is functioning properly.

---

## ✅ Features

- Displays a status message when run
- Uses the built-in `wsl --status` command
- Intended for post-update WSL verification
- Lightweight and easy to execute

---

## 🛠️ Script Details

**Script Name**: `Check-WSL-PostUpdate-AutoReboot.ps1`  
**Location**: `C:\Scripts` (or any path you prefer)  
**Language**: PowerShell (.ps1)

### 📋 Script Contents:
```powershell
Write-Host "WSL Post-Update Check Script Running..." -ForegroundColor Cyan
wsl --status
🚀 How to Use
1. Create the Script

Open Notepad (or your preferred text editor) and paste the contents above.
2. Save the Script

    Save as: Check-WSL-PostUpdate-AutoReboot.ps1

    File type: All Files

    Encoding: UTF-8 or ANSI

    Confirm it doesn't save as .ps1.txt accidentally

3. Run the Script in PowerShell

& "C:\Scripts\Check-WSL-PostUpdate-AutoReboot.ps1"

Make sure your execution policy allows running scripts. If needed, use:

Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

🧪 Testing & Troubleshooting

    If you encounter a path or filename error, double-check that:

        The file extension is .ps1

        The script is saved in the correct directory

        PowerShell has permissions to run the file

📌 Use Case

This script is useful for:

    Developers and sysadmins using WSL

    Verifying WSL functionality after Windows updates or system restarts

    Ensuring a smooth dev environment setup

📁 Repository Structure

WSL-PostUpdate-Check-Script/
├── Check-WSL-PostUpdate-AutoReboot.ps1
└── README.md

🧠 Author Notes

This simple automation tool was created to streamline WSL checks and can be integrated into larger post-update automation scripts or system monitoring tools.
MIT License

Copyright (c) 2025 Jacqueline Gibson-Bradley

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell     
copies of the Software, and to permit persons to whom the Software is        
furnished to do so, subject to the following conditions:                      

The above copyright notice and this permission notice shall be included in    
all copies or substantial portions of the Software.                           

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR    
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,      
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE   
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER        
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN     
THE SOFTWARE.
