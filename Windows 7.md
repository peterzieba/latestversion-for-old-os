# Overview
A collection of the latest versions of common software that still work for Windows 7 SP1.
* Not included is software for which the latest version still works fine on Windows 7.

# Updates
* Base updates (good place to start):
  * [Servicing-Stack-KB3177467](https://www.catalog.update.microsoft.com/search.aspx?q=kb3177467)
    * [Rollup-KB3125574](https://www.catalog.update.microsoft.com/Search.aspx?q=KB3125574)
* Windows Help does not support old .HLP files
    - Install the WinHelp viewer (KB917607) for your specific version of Windows
    - Windows6.1-KB917607-x64.msu
    - Windows6.1-KB917607-x86.msu
    - [https://archive.org/download/kb917607](https://archive.org/download/kb917607)
    - [https://www.helpscribble.com/KB917607.html](https://www.helpscribble.com/KB917607.html)

# Programming
* Python
  * Officially Supported: [Python 3.8.15 - Oct. 11, 2022](https://www.python.org/downloads/release/python-3815/)
  * Unofficially Supported: [>v3.13 via https://github.com/adang1345/PythonWin7](https://github.com/adang1345/PythonWin7)

# .NET Framework
[Version 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-offline-installer) is probably the latest that will work with Windows 7.<br>
On a fresh Windows 7 SP1 install with no updates, it may fail to install with "A certificate chain could not be built to a trusted root authority".

# Video
* [OBS Version 27.2.4](https://github.com/obsproject/obs-studio/releases/tag/27.2.4)
  * You will need [`directx_Jun2010_redist.exe`](https://www.microsoft.com/en-us/download/details.aspx?id=8109) first. Extract and run `DXSETUP.EXE`
 
# Web
* Firefox Setup 115 esr
  * https://ftp.mozilla.org/pub/firefox/releases/115.23.1esr/win64/en-US/Firefox%20Setup%20115.23.1esr.exe
  * 115.23.1esr is the latest as of 5/18/25
  * Check https://ftp.mozilla.org/pub/firefox/releases/ to see what the latest 115 esr release is.
* Brave v1.47.186
  * [x64](https://github.com/brave/brave-browser/releases/download/v1.47.186/BraveBrowserStandaloneSetup.exe)
  * [x86](https://github.com/brave/brave-browser/releases/download/v1.47.186/BraveBrowserStandaloneSetup32.exe)
 
# Misc
* Adobe Acrobat - `AcroRdrDC2500120432_en_US.exe`
** https://get.adobe.com/reader/otherversions
