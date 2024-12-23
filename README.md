# 🪟Windows Usability Features Guide
![image](https://github.com/user-attachments/assets/3c4d8079-2e60-4532-a97a-f42e7c2b75be)
![image](https://github.com/user-attachments/assets/91186e12-23d7-4576-bad3-ef07b92636c6)
![image](https://github.com/user-attachments/assets/15340355-c310-4dc6-abda-bac6ddb8067d)


## Table of Contents
1. Introduction
2. Accessibility Features
3. Productivity Tips
4. Customization Options
5. Troubleshooting

## Formats
Quick Heal - Data Backup & Restore Backup
-----------------------------------------------------------
Data Backup automatically and periodically (multiple times a day), takes a backup of all your important and common files including PDF, Microsoft Office files, Tally accounting data, and Busywin accounting data in a safe folder on your computer. If you update any file, the feature will automatically take the backup of the latest copy.

This safe folder is created by the Data Backup feature of Quick Heal. Taking the backup of the data is important as you can restore your data whenever required. For example, if any Ransomware encrypts the data on your computer, you can easily restore the backed up data without falling a victim to such threats. Hence it is recommended that you always keep Data Backup turned on. However, this feature is turned on by default. 

For more information, please visit http://blogs.quickheal.com/how-to-recover-files-after-a-ransomware-attack.
-----------------------------------------------------------
# Data of the following file types is backed up by default.
---------------------
• Text Files: .TXT
• Document Files: .DOC, .DOCX, .XLS, .XLSX, .PPT, .PPTX, .PDF, .WPS, .WPT, .RTF, .ET, .DOCM, .XLSM, .PPTM, .ETT, .DPT, .DPS, .ODS, .ODP, .ODG, .ODT
• Email Files: .EML
• Accounting Files: .001, .247, .500, .900, .989, .TCP, .TSF, .TSM, .BDS, .SYS, .MDF, .LDF, .BKP, .DB, .CS

Custom file type: More files that you can select to back up the data.
---------------------
• Image/Photo Files: .PCK, .TIFF, .WPG, .BMP, .GIF, .JPG, .JPEG, .WMP, .PNG, .TIF
• Creative Artwork Files:  .AI, .EPS, .PCX, .PSD, .CDR
• Movie Files:  .AVI, .VOB, .MPV, .MPEG, .MPG, .MPE, .MPA, .RM, .QT, .MP4
• Sound Files: .WMV, .WMA, .MP3

Note: You can add some more file types (file extensions) to take their backup using Add Extension. 
-----------------------------------------------------------
# Enabling/Disabling Data Backup
-----------------------------------------------------------
1. Open Quick Heal. 
2. On the left pane, click Privacy and then click Data Backup.
3. Turn Data Backup on or off as per your requirement.
4. If you turn off Data Backup, you are prompted for confirmation. Click Yes.
------------------------------------------------------------------------------

## File Extension
.exe
   
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
  ![image](https://github.com/user-attachments/assets/d0b3a805-a74e-4027-8ed5-ec425edb42b2)

# 🏃‍➡️Run
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

to open control panel
```
control panel
```

to open computer management
```
compmgmt.msc
```
# 🧹Cleanup  
```
%temp%
```

```
tree
```

```
prefetch
```

![image](https://github.com/user-attachments/assets/f367c9b1-2f90-46f1-920d-85dd5f390f1f)

# 💬cmd
```
tasklist
```

```
taskkill /f /im google.exe
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

# to see active connection in port 
```
netstat -ano
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
    
