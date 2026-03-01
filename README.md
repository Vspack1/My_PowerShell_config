# My_PowerShell_config

PowerShell terminal setup for Windows (CLI-focused, Linux vibe).

## ✨ Features
- PowerShell 7+
- Oh My Posh prompt
- Fastfetch on startup
- Useful aliases & functions
- `tools` command to list installed CLI tools
- Scoop-based CLI workflow

## 📦 Requirements
- Windows 10/11
- PowerShell 7+
- Git

## 🚀 Installation

### 

1️⃣ Clone repo
```powershell
git clone https://github.com/Vspack1/My_PowerShell_config.git
cd My_PowerShell_config

2️⃣ Backup current profile
copy $PROFILE "$PROFILE.bak"

3️⃣ Apply profile
copy .\Microsoft.PowerShell_profile.ps1 $PROFILE

4️⃣ Install Scoop (if not installed)
irm get.scoop.sh | iex

5️⃣ Install recommended CLI tools
scoop install fastfetch fd ripgrep fzf git yazi zoxide jq

6️⃣ Restart PowerShell 🎉
🧪 Usage

~~: Run fastfetch to show system info

~~: Run tools to list installed CLI tools

🧩 Files

~~: Microsoft.PowerShell_profile.ps1 → main PowerShell config

~~: myprofile.omp.json → Oh My Posh theme

~~: Modules/ → custom modules (optional)

📸 Preview:
<img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/0b0b9fde-e04c-4f43-876e-cfa236110870" />

⚠️ Notes:

This setup is CLI-focused

GUI apps are not included
