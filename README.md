# [WinExternal](https://www.maravento.com/p/winexternal.html)

<!-- markdownlint-disable MD033 -->

[![status-stable](https://img.shields.io/badge/status-stable-green.svg)](https://github.com/winexternal)
[![last commit](https://img.shields.io/github/last-commit/maravento/winexternal)](https://github.com/maravento/winexternal)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/maravento/winexternal)
[![Twitter Follow](https://img.shields.io/twitter/follow/maraventostudio.svg?style=social)](https://twitter.com/maraventostudio)

<table align="center">
  <tr>
    <td align="center">
      <span>English</span> | <a href="README-es.md">Español</a>
    </td>
  </tr>
</table>

**WinExternal** is a project that compiles several Microsoft offline installers for Windows, into one silent, unattended launcher.

## DATA SHEET

---

| File | OS | Size |
| :---: | :---: | :---: |
| [WinExternal.exe (.zip)](https://mega.nz/file/TR1kgKIb#SKPQoI2JkVL9bG4alBTERsv-220ydLh8YxZ76eEMsyc) | Windows 7/10/11 x86 x64 | 997,9 MB |

## HOW TO USE

---

Disable your Antivirus, Antimalware, SmartScreen or any other security solution in your Operating System, close all windows and check the date and time of your PC is correct. Download WinExternal.exe (.zip), unzip it to your desktop, execute it with double click (accept privileged execution) and follow the instructions on the screen.

## SELECTOR

---

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-selector.png)](https://www.maravento.com/p/winexternal.html)

WinExternal contains standalone packages. Select the one of your preference.

### OS

All packages are supported on Windows 10/11 x64 only, except [Legacy](https://github.com/maravento/winexternal#microsoft-legacy), which is supported on Windows 7 x86 only and whose components have reached End-of-Life (EOL) / End-of-Support (EOS). Backward compatibility with previous versions of Windows 10/11 22H2 or Windows Server versions is not guaranteed. If your OS does not support the component you selected, the following window will appear:

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-abort.png)](https://www.maravento.com/p/winexternal.html)

### Microsoft Visual C++ Redistributable Runtimes

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-visualc.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Visual Basic/C++ Runtime x86 - 1.1.0
- Microsoft Visual C++ 2005 Redistributable x86 x64 - 8.0.61187
- Microsoft Visual C++ 2008 Redistributable x86 x64 - 9.30729.7523
- Microsoft Visual C++ 2010 Redistributable x86 x64 - 10.0.40219
- Microsoft Visual C++ 2012 Redistributable x86 x64 (Additional and Minimum Runtime) - 11.0.61135
- Microsoft Visual C++ 2013 Redistributable x86 x64 (Additional and Minimum Runtime) - 12.0.40664
- Microsoft Visual C++ 2022 Redistributable x86 x64 (Additional and Minimum Runtime) - 14.44.35208

#### Add-On

- Microsoft Visual Studio Tools for Applications 2022 x64 - 17.0.35906
- Microsoft Visual Studio 2010 Tools for Office Runtime x64 - 10.0.609922

### Microsoft .NET Framework Runtime v3.5 SP1

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-net35.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET Framework v3.5 SP1 Standalone Installation Package (for Windows 10 22H2 x64 and Windows 11 24H2 x64)

#### Important About Microsoft .NET Framework Runtime v3.5 SP1

- Installation can fail for many reasons. In this case, unzip `WinExternal.exe` on your operating system drive (e.g.: `c:\`), go to `WinExternal\NET35\alternative` and run the `Install .NET Framework 3.5 via DISM.cmd` script with administrative privileges (ISO image required). For more information see `WinExternal\NET35\alternative\readme.txt`.
- Only OS English/Spanish

### Microsoft .NET Framework Runtime v4.8.1

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-net481.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET Framework Runtime 4.8.1 Standalone Installation Package (for Windows 10/11 EN/SP for 20H2 or Later) - 4.8.9037.6

#### Important About Microsoft .NET Framework Runtime v4.8.1

- Includes native support for Arm64, Accessible Tooltips, Windows Forms – Accessibility Improvements. For more information, check: [Release Notes](https://github.com/microsoft/dotnet/blob/master/releases/net481/README.md)
- Only use this installer in case traditional methods fail (WSUS, SCCM or similar).

### Microsoft .NET Desktop Runtime

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-netruntime.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET 9.0.5 Desktop Runtime x64 LTS (Active)
- Microsoft .NET 8.0.16 Desktop Runtime x64 LTS (Active)
- Microsoft .NET 6.0.36 Desktop Runtime x64 LTS (End of Support EOS)

check with: / verifique con:

```bash
dotnet --info
```

### Microsoft Edge

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-edge.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Edge for Business x64 - 137.0.3296.52
- Microsoft Edge WebView2 Evergreen Standalone Installer x64 - 137.0.3296.52

#### Important About Edge

Edge and WebView2 are now pre-installed on most devices running Windows 10 or higher, are automatically updated, and are integrated as a core component of the operating system, so they do not support uninstallation by traditional methods. Selecting this option from the WinExternal selector menu will only install these components, if they do not exist on your operating system. Check [Feedback](https://github.com/MicrosoftEdge/WebView2Feedback/issues/3780).


### Microsoft Legacy

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-legacy.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Directx End-User Runtimes - 9.29.1974.1 (EOS Jun 2010)
- Microsoft .NET Framework Runtime v4.8 - 4.8.4115.0 ENU | 4.8.3761.0 ESN
- Microsoft Visual J# Version 2.0 Redistributable Package - Second Edition (x86 x64) (EOS Jul 2016)
- Microsoft Visual Studio 2010 F# 2.0 SP1 (EOS Jul 2020)
- Microsoft XNA Framework Redistributable v4.0 - 4.0.20823.0

### Telemetry

WinExternal sends information to the developer, only for the purpose of verifying that the installation has been completed successfully. This information is used exclusively for statistical purposes and to improve the installer, without collecting personal data or compromising user privacy. Example:

```bash
Package Installation
Hostname=DESKTOP-AJ4JSC8
User=Usuario
Date=wed. 13/11/2024 Time= 6:44:17,39
Status=Installed
Package: WinExternal
```

### IMPORTANT

- [Microsoft .NET Framework Runtime v4.8 is included in Windows 10 May 2019 and later](https://docs.microsoft.com/en-us/dotnet/framework/install/on-windows-10#net-framework-48)
- [Microsoft Silverlight no longer run on WinExternal (EOS Oct 2021)](https://support.microsoft.com/en-us/windows/silverlight-end-of-support-0a3be3c7-bead-e203-2dfd-74f0a64f1788)
- [Microsoft XML Core Services (MSXML) no longer run on WinExternal (EOS Oct 2021)](https://learn.microsoft.com/en-us/lifecycle/products/microsoft-xml-core-services-40)
- [Since Microsoft Visual Studio 2015 share the same redistributable files](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)
- [Microsoft Visual Studio Tools for Application 2019 - EOS](https://www.microsoft.com/en-us/download/details.aspx?id=58317)

### WORKTOOLS

- [7zSFX Builder](https://sourceforge.net/projects/s-zipsfxbuilder/)
- [curl for Windows](https://curl.se/windows/)
- [iconarchive](http://www.iconarchive.com/show/fs-icons-by-franksouza183/Places-folder-windows-icon.html)
- [icon-icons](https://icon-icons.com/icon/dot-net-original-logo/146546)
- [Microsoft DirectX End-User Runtime](https://www.microsoft.com/en-us/download/details.aspx?id=8109)
- [Microsoft Edge Enterprise](https://www.microsoft.com/en-us/edge/business/download?form=MA13FJ)
- [Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)
- [Microsoft .NET Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet)
- [Microsoft NetFramework Runtime](https://dotnet.microsoft.com/download/dotnet-framework)
- [Microsoft Visual C++ Runtime](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)
- [Microsoft Visual J# Redistributable Package 2.0](https://www.microsoft.com/es-es/download/details.aspx?id=4712)
- [Microsoft Visual Studio 2010 F# 2.0](http://web.archive.org/web/20200721134946/https://www.microsoft.com/en-us/download/details.aspx?id=15834)
- [Microsoft Visual Studio Tools for Application 2022](https://www.microsoft.com/en-us/download/details.aspx?id=105123)
- [Microsoft XNA Framework Redistributable](https://www.microsoft.com/en-us/download/details.aspx?id=27598)
- [Resource Turner](http://www.restuner.com/)
- [vcredist](https://github.com/abbodi1406/vcredist/releases)
- [WinZenity](https://github.com/maravento/vault/tree/master/winzenity)

## NOTICE

---

- This project includes third-party components.
- Changes must be submitted via Issues. Pull requests are not accepted.

## STARGAZERS

---

[![Stargazers](https://bytecrank.com/nastyox/reporoster/php/stargazersSVG.php?user=maravento&repo=winexternal)](https://github.com/maravento/winexternal/stargazers)

## CONTRIBUTIONS

---

We thank all those who contributed to this project.

## SPONSOR THIS PROJECT

---

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/maravento-paypal.png)](https://paypal.me/maravento)

## PROJECT LICENSES

---

[![GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl.txt)
[![CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC_BY--NC--ND_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.en)

## DISCLAIMER

---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
