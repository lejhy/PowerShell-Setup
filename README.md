Install MesloLGSNF font #The other fonts shouldn't be needed, although they might become handy at some point
Run registry file #Creates/overwrites registry values at KEY_CURRENT_USER/Console, so might be worthhwile to back it all up
Open regedit at HKEY_CURRENT_USER/Console #contains the settings of all console applications
Delete all non-default values of all folders inside #subfolders contain executable-specific settings that overwrite the global settings
Paste shortcuts into "C:\Users\flejh\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Windows PowerShell" #overwrite start menu shortcuts, original ones overwrite the registry settings
Paste profile file into "C:\Users\flejh\Documents\WindowsPowerShell" #adjust as needed
Download oh-my-posh and posh-git modules and paste module folders into "C:\Program Files\WindowsPowerShell\Modules" #Not sure about dependencies, but other modules contained in the current setup are: Pester, PSreadline, PSScriptAnalyzer, PowerShellGet, PackageManagement, Micrososft.PowerShell.Operation.Validation
Paste the 'flejh.psm1' profile into the oh-my-posh module theme folder (eg. "C:\Program Files\WindowsPowerShell\Modules\oh-my-posh\2.0.223\Themes") 