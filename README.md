# miniExplorer
Function that launches a form that resembles Windows Explorer.  The reason this was built is due to STA PowerShell GUI scripts, and issues with FolderBrowserDialog.

# Example
If you have a PowerShell script that requires a user to select a .csv file, you can run:`r`n"Start-miniExplorer -ShowFilesWithExtensionOnly csv"`r`nThis will only show .csv files within miniExplorer.

# Screenshot

![Alt text](http://i.imgur.com/L8Te30g.png "miniExplorer")
