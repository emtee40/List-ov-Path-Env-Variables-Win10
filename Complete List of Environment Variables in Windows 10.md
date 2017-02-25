Complete List of Environment Variables in Windows 10
====================================================

# ![information][6]   Information

> [**Environment variables][7]** are a set of dynamic named values that can affect the way running processes will behave on a computer. The variables can be used both in scripts and on the command line. Environment variables makes it easy when certain standard directories and parameters need to be referenced but where the actual locations or names can vary from computer to computer.

This tutorial will show you a complete list of **environment variables** that can be used to reference standard directories and parameters in **Windows 10**.

## ![Note][8] Note

**User environment variables** are stored in the registry key below:

```reg
HKEY_CURRENT_USEREnvironment
```

**System environment variables** are stored in the registry key below:

```reg
HKEY_LOCAL_MACHINESYSTEMCurrentControlSetControlSession ManagerEnvironment
```

You can open a **Command Prompt**, type `set`, and press Enter to display all current environment variables on your PC.

You can open **PowerShell**, type `Get-ChildItem Env:`, and press Enter to display all current environment variables on your PC.


## Table of Environmental Variables

| **Environment Variables** |                       **Values** (may vary)                       |
| ------------------------- | ----------------------------------------------------------------- |
| %ALLUSERSPROFILE%         | C:ProgramData                                                     |
| %APPDATA%                 | C:Users(user-name)AppDataRoaming                                  |
| %CD%                      | Current directory full path                                       |
| %CMDCMDLINE%              | Returns exact command line used to start current cmd.exe session. |
| %CMDEXTVERSION%           | Number of current command processor extensions.                   |
| %CommonProgramFiles%      | C:Program FilesCommon Files                                       |
| %CommonProgramFiles(x86)% | C:Program Files (x86)Common Files                                 |
| %CommonProgramW6432%      | C:Program FilesCommon Files                                       |
| %COMPUTERNAME%            | BRINK-PC                                                          |
| %COMSPEC%                 | C:WindowsSystem32cmd.exe                                          |
| %DATE%                    | Current date in format determined by _Date_ command               |
| %ERRORLEVEL%              | Number defining exit status of previous command or program        |
| %HOMEDRIVE%               | C:                                                                |
| %HOMEPATH%                | C:Users(user-name)                                                |
| %LOCALAPPDATA%            | C:Users(user-name)AppDataLocal                                    |
| %LOGONSERVER%             | [\MicrosoftAccount][9]                                            |
| %NUMBER_OF_PROCESSORS%    | 8                                                                 |
| %OS%                      | Windows_NT                                                        |
| %PATH%                    | C:\WINDOWS<br/>C:WINDOWS\system32<br/>C:WINDOWS\System32\Wbem<br/>C:\Windows\system32\WindowsPowerShell\v1.0 |
| %PATHEXT% |  COM;.EXE;.BAT;.CMD;.VBS;.VBE;.JS;.JSE;.WSF;.WSH;.MSC |
| %PROCESSOR_ARCHITECTURE% |  AMD64 |
| %PROCESSOR_IDENTIFIER% |  Intel64 Family 6 Model 60 Stepping 3, GenuineIntel |
| %PROCESSOR_LEVEL% |  6 |
| %PROCESSOR_REVISION% |  3c03 |
| %ProgramData% |  C:ProgramData |
| %ProgramFiles% |  C:Program Files |
| %ProgramFiles(x86)% |  C:Program Files (x86) |
| %ProgramW6432% |  C:Program Files |
| %PROMPT% |  Code for current command prompt format. Code is usually $P$G |
| %PSModulePath% |  C:Windowssystem32WindowsPowerShellv1.0Modules |
| %PUBLIC% |  C:UsersPublic |
| %RANDOM% |  To get random number between 0 and 32767 |
| %SessionName% |  When logging on directly to machine, returns "Console".<br/>When client connects via terminal server session, is combination of<br/>connection name, followed by pound symbol {#} and session number.|
| %SystemDrive% |  C: |
| %SystemRoot% |  C:Windows |
| %TEMP% |  C:Users(user-name)AppDataLocalTemp |
| %TIME% |  Current time in format determined by _Time_ command |
| %TMP% |  C:Users(user-name)AppDataLocalTemp |
| %USERDOMAIN% |  BRINK-PC |
| %USERDOMAIN_ROAMINGPROFILE% |  BRINK-PC |
| %USERNAME% |  (user-name) |
| %USERPROFILE% |  C:Users(user-name) |
| %WINDIR% |  C:Windows |

**Credits**:
> [Brink][2]
> Administrator
> ![][4]
>

> **Related Tutorials**
>
> * * *
>
>
>
> * [Complete List of Windows 10 CLSID Key (GUID) Shortcuts][10]
> * [Complete List of Windows 10 Shell Commands][11]
> * [List of Rundll32 Commands for Windows 10][12]
>

[1]: https://cdn.tenforums.com/customavatars/avatar2_9.gif "Brink's Avatar"
[2]: https://www.tenforums.com/members/brink.html
[3]: https://cdn.tenforums.com/images/ranks/MVP_insider.png
[4]: https://cdn.tenforums.com/images/ranks/tef_admin1.png
[5]: https://cdn.tenforums.com/images/buttons/printer.gif "Show Printable Version"
[6]: https://cdn.tenforums.com/images/infosmall10.png "information"
[7]: http://en.wikipedia.org/wiki/Environment_variable
[8]: https://cdn.tenforums.com/images/notesmall10.png "Note"
[9]: https://www.tenforums.com/tutorials/file://\MicrosoftAccount
[10]: https://www.tenforums.com/tutorials/3123-clsid-key-guid-shortcuts-list-windows-10-a.html
[11]: https://www.tenforums.com/tutorials/3109-shell-commands-windows-10-a.html
[12]: https://www.tenforums.com/tutorials/77458-rundll32-commands-list-windows-10-a.html

**Print:** ![Show Printable Version][5]