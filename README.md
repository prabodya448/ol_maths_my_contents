# O/L Maths Content - File List Update Guide

මේ Folder එකේ තියෙන අලුත් images එක්ක `files.txt` එක update කරගන්න පහළ පියවර අනුගමනය කරන්න.

### පියවර (How to run):

1. මේ folder එකේ ඉද්දි VS Code එකේ Terminal එක ගන්න (`Ctrl` + `~`).
2. පහළ තියෙන Command එක copy කරලා paste කරන්න.
3. Enter කරන්න.

### PowerShell Command එක:

```powershell
Get-ChildItem -Recurse -File | Select-Object -ExpandProperty FullName > files.txt