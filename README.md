# JustMsOfficeInstaller

Microsoft Office 365 Installer for Windows 10/11 x64
this script allows you to download and install latest office 365 excel,word and powerpoint with no additional programs installed

# Initialization

first you need to download Office Deployment Tool from microsoft website
```bash
https://www.microsoft.com/en-us/download/details.aspx?id=49117
```
run officedeploymenttool to extract office.exe

download the JustMsOfficeInstaller from Releases or git clone with
```bash
git clone https://github.com/denizomer1/JustMsOfficeInstaller
```

add office.exe to the JustMsOfficeInstaller folder

# Download and Install Office

First use this script to download office 365 files
```bash
download_office.cmd
```
after install with
```bash
install_office.cmd
```
Backup the JustMsOfficeInstaller folder so you can install offline without having to download again

# Update Office Installation Files
run this script to update office installation files with latest
```bash
download_office.cmd
```

# Office Activation
Use Office 365 Subscription to activate office or use MAS
```bash
https://github.com/massgravel/Microsoft-Activation-Scripts
```
