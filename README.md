# Foto-Org

An application for scanning, de-duplicating, and organising your photo library.

## Features
- Scan a folder and all subfolders for photos and duplicates
- Place duplicate images in groups of similarity
- Mark low detail photos
- Identify best quality or most original photo of duplicates
- User can remove duplicate images from the duplicate group (photo is then considered unique)
- Remove duplicate groups (photos from group are then all considered unique)
- User can remove Low Detail mark from photos
- User can delete all selected or individual photos
- User can set scan accuracy and other settings
- Copy non duplicates to one of three different folder systems, single folder, numerical only date, human readable date

## Download
[⬇️ Download Latest Release](https://github.com/leocadle/foto-org-public/releases/latest)

### Installation
1. Download and unzip the release package
2. Right-click `Install.ps1` → **Run with PowerShell**

## Requirements
- Windows 10 or 11
- .NET 8
- Visual Studio 2022 with WinUI workload installed

## Roadmap
- [X] Scan for duplicate photos
- [X] Show groups of duplicates
- [X] Identify best photo of duplicates
- [ ] Identify low information photos
- [ ] Identify out of focus photos
- [X] Allow deletion of duplicates and other photos
- [X] Allow duplicates and bad photos to be removed from duplicates/bad photos groups
- [X] Add settings to control various factors around files and scanning
- [X] Copy non duplicates to a new folder with a date hierarchy

## License
MIT
