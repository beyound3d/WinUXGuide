# 🪟Windows Usability Features Guide
## Table of Contents
1. Introduction
2. Accessibility Features
3. Productivity Tips
4. Customization Options
5. Troubleshooting
   
##  Accessibility Features
### Narrator
- **Start Narrator:** Press `Ctrl + Windows + Enter`.
- **Stop Narrator:** Press the same

## Productivity Tips
### Task View
- **Open Task View:** Press `Windows + Tab`
### Virtual Desktops
- **Create New Desktop:** Press `Windows + Ctrl + D`.
- **Switch Desktops:** Press `Windows + Ctrl + Left/Right Arrow`

## Customization Options
### Customize Start Menu
- **Pin/Unpin Tiles:** Right-click on the Start menu item and select `Pin to Start` or `Unpin from Start`

## Troubleshooting
  **Run System File Checker:** Open Command Prompt as admin and type `sfc /scannow`
# Run
to open disk management
- ```
  diskmgmt.msc
  ```

to open system configuaration
 - ```
   msconfig
   ```

to open to check system info open some in cmd
 - ```
   systeminfo
   ```

to open system properties   
 - ```
   sysdm.cpl
   ```

to open Disk cleanup
 - ```
   cleanmgr
   ```

to open services
 - ```
   services.msc
   ```

to open task manager   
 - ```
   taskmgr  
   ```

# Cleanup   

# cmd
```
tasklist
```

```
ipconfig
```

```
ipconfig  /all
```

```
ipconfig  /all | findstr DNS
```

```
ipconfig  /release
```

```
ipconfig  /renew
```

```
ipconfig  /renew "Wi-Fi"
```

```
ipconfig /displaydns
```

```
ipconfig /displaydns | clip
```

```
nslookup google.com
```

```
cls
```

```
getmac  /v
```

```
powercfg /energy
```

```
powercfg /batteryreport
```

```
assoc
```

```
assoc  .mp4=VLC.vlc
```

```
chkdsk /f
```

```
chkdsk /r
```

```
sfc /scannow
```

```
tracert
```

```
netstat
```

```
ping
```

```
mode 800
```

```
arp -a
```

```
pathping google.com
```

```
route
```

```
hostname
```

```
getmac
```

```
nbtstat -n
```

```
tsklist
```

```
tskkill /PID 2000
```

```
systeminfo
```

```
netsh?
```

```
net view
```

```
net share
```

```
wmic
```

```
wmic bios get smbiosbiosversion
```

```
wmic
```

```
msinfo32
```

# making .bat file (batch script)

# usefullness
```
netsh wlan show profiles
```

```
netsh wlan show profile name="Tanu's Galaxy A32" key=clear
```

# open powershell as adminstator from cmd
```
powershell Start-Process powershell -Verb runAs
```

# open cmd AS ADMINSTRATOR from powershell
```
Start-Process cmd -Verb runAs
```
     
## 💁‍♂️Contributing
Feel free to contribute to this repository by submitting pull requests.    
    
