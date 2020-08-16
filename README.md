
## Windows Terminal.reg
Add to context menu options: **Windows Terminal**.

This .reg file create Key: 

***HKEY_CURRENT_USER\SOFTWARE\Classes\Directory\Background\shell\Windows Terminal\command*** 

and add entry: 

***%LOCALAPPDATA%\\Microsoft\\WindowsApps\\wt.exe -d .***

## Windows Terminal as Admin.reg
Add to context menu options: **Windows Terminal as Admin**.

This .reg file create Key: 

***HKEY_CURRENT_USER\SOFTWARE\Classes\Directory\Background\shell\Windows Terminal as Admin\command*** 

and add entry: 

***powershell.exe -windowstyle hidden "start-process wt.exe -Verb runas -ArgumentList '-d .'"***

## Windows Terminal (preview).reg
Add to context menu options: **Windows Terminal (preview)**.

This .reg file create Key: 

***HKEY_CURRENT_USER\SOFTWARE\Classes\Directory\Background\shell\Windows Terminal (preview)\command*** 

and add entry: 

***%LOCALAPPDATA%\\Microsoft\\WindowsApps\\Microsoft.WindowsTerminalPreview_8wekyb3d8bbwe\\wt.exe -d .***


