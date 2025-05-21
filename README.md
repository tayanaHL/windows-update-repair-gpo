# Windows Update Repair + Group Policy Testing

A hands-on troubleshooting project that simulates a Windows Update failure, uses built-in Windows tools to repair the issue, and configures update policies using the Group Policy Editor.

---

## 🛠️ Tools Used

- Windows 10 VM (VirtualBox)
- Services.msc
- Windows Update Troubleshooter
- Group Policy Editor (gpedit.msc)
- CMD (as Admin)

---

## 🎯 Project Objectives

- Simulate a Windows Update failure
- Troubleshoot and repair the issue using built-in Windows tools
- Configure Group Policy settings for updates

---

## 🔍 Step-by-Step Process

### 1. Simulate an Update Error

- Open `services.msc`
- Right-click **Windows Update** service → Click **Stop**
- Go to **Settings > Update & Security > Windows Update**
- Click **Check for Updates** → You should receive an error


---

### 2. Run the Troubleshooter

- Go to **Settings > Update & Security > Troubleshoot**
- Select **Windows Update** → Run Troubleshooter
- Let it apply any fixes and show results


---

### 3. Open Group Policy Editor

- Press `Win + R` → Type `gpedit.msc` → Enter  
  *(If it doesn’t open, your Windows edition may not include it)*

- Navigate to:  
  `Computer Configuration > Administrative Templates > Windows Components > Windows Update`

- Modify policies like:
  - **Configure Automatic Updates**
  - **Specify intranet Microsoft update service location**
  - **No auto-restart with logged on users**


---

## ✅ Outcome

- Simulated a common update error
- Repaired the issue using the Windows Update Troubleshooter
- Explored and adjusted Windows Update Group Policies
- Practiced real-world Help Desk troubleshooting methods

---



## 🔐 Skills Demonstrated

- Windows troubleshooting
- Group Policy configuration
- Virtual machine management
- System diagnostics


