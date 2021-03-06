
### PowerShell v6-RC Core

- [Strict-mode-ErrorRecord-formatting](Basic\Strict-mode-ErrorRecord-formatting)
-- Fixed

### PowerShell v6-beta.9 Core

- [PowerShell.exe/Not-current-version](PowerShell.exe/Not-current-version)
-- The trap is back due to the renamed powershell.exe to pwsh.exe
- [PowerShell.exe/Version-parameter](PowerShell.exe/Version-parameter)
-- Anything after `-Version` is silently ignored.

### PowerShell v6-beta.7 Core

- [PowerShell.exe/Not-current-version](PowerShell.exe/Not-current-version)
-- Fixed the v6 specific issue (Example 2, Not-same-exe.ps1)
- [PowerShell.exe/Version-parameter](PowerShell.exe/Version-parameter)
-- `-Version` has different meaning in v6 (revealed in this update).
- [PowerShell.exe/Version-scriptblock-host-problem](PowerShell.exe/Version-scriptblock-host-problem)
-- `-Version` has different meaning in v6 (revealed in this update).

### PowerShell v6-beta.5 Core

- [PowerShell.exe/Switch-parameter-with-value](PowerShell.exe/Switch-parameter-with-value)
-- Allow passing $true/$false as a parameter to scripts using powershell.exe -File

### PowerShell v6-beta.3 Core

- [PowerShell.exe/Positional-Command-File](PowerShell.exe/Positional-Command-File)
-- Breaking change: Change positional parameter from `-Command` to `-File`
- [Cmdlets/Start-Transcript/v5-Unexpected-stop](Cmdlets/Start-Transcript/v5-Unexpected-stop)
-- Fixed

### PowerShell v6-beta.1 Core

- [Basic/DynamicParam/ExpectingInput-is-false](Basic/DynamicParam/ExpectingInput-is-false)
-- Fixed
- [Basic/Properties-of-XmlNode](Basic/Properties-of-XmlNode)
-- Fixed "Adapted properties accept only string values"
- [Cmdlets/ConvertFrom-Json/v6-long-integers](Cmdlets/ConvertFrom-Json/v6-long-integers)
-- Integers are returned as `[long]`, not `[int]`
- [Cmdlets/ConvertTo-Json/Array-as-PSObject](Cmdlets/ConvertTo-Json/Array-as-PSObject)
-- Fixed
- [PowerShell.exe/Not-current-version](PowerShell.exe/Not-current-version)
-- Minor traps on playing with v6 Core on Windows
