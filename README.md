# [WinExternal](https://www.maravento.com/p/winexternal.html)

[![status-stable](https://img.shields.io/badge/status-stable-green.svg)](https://github.com/winexternal)
[![last commit](https://img.shields.io/github/last-commit/maravento/winexternal)](https://github.com/maravento/winexternal)
[![Twitter Follow](https://img.shields.io/twitter/follow/maraventostudio.svg?style=social)](https://twitter.com/maraventostudio)

**WinExternal** is a project that compiles several Microsoft offline installers for Windows, into one silent, unattended launcher.

**WinExternal** es un proyecto que recopila varios instaladores fuera de línea de Microsoft para Windows, en un lanzador desatendido y silencioso.

## DATA SHEET

---

|File (mega)|File (pcloud)|OS|Size|
| :---: | :---: | :---: | :---: |
|[WinExternal.exe (.zip)](https://mega.nz/file/PNUQhA4Z#u3UyRA5dQ5X9a2kYSL76QUK0GBnhSaGuvtLjcYI6iIM)|[WinExternal.exe (.zip)](https://u.pcloud.link/publink/show?code=M0J)|Windows 7/8/10/11 x86 x64|712.1 MB|

## HOW TO USE

---

Disable your Antivirus, Antimalware, SmartScreen or any other security solution in your Operating System, close all windows and check the date and time of your PC is correct. Download WinExternal.exe (.zip), unzip it to your desktop, execute it with double click (accept privileged execution) and follow the instructions on the screen

Desactive su Antivirus, Antimalware, SmartScreen o cualquier otra solución de seguridad en su Sistema Operativo, cierre todas las ventanas y verifique la fecha y hora de su PC sea la correcta. Descargue WinExternal.exe (.zip), descomprimirlo en el escritorio, ejecutarlo con doble clic (acepte la ejecución con privilegios) y siga las instrucciones en pantalla

## SELECTOR

---

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-selector.png)](https://www.maravento.com/p/winexternal.html)

WinExternal contains standalone packages. Select the one of your preference / WinExternal contiene paquetes independientes. Seleccione el de su preferencia

### Visual C++ Redistributable Runtimes

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-visualc.png)](https://www.maravento.com/p/winexternal.html)

- Visual C++ 2005 Redistributable x86 x64 (8.0.50727.6229)
- Visual C++ 2008 Redistributable x86 x64 (9.30729.7523)
- Visual C++ 2010 Redistributable x86 x64 (10.0.40219.473)
- Visual C++ 2012 Additional and Minimum Runtime x86 x64 (11.0.61135.400)
- Visual C++ 2013 Additional and Minimum Runtime x86 x64 (12.0.40664.0)
- Visual C++ 2019 Additional and Minimum Runtime x86 x64 (14.29.30130.2)
- Visual C++ 2022 Additional and Minimum Runtime x86 x64 (14.36.32532.0)
- Visual Legacy Runtimes x86: Basic/C++ 2002 (7.0.9975.0) - 2003 (7.10.6119.0)
- Visual Studio 2010 Tools for Office Runtime x86 x64 (10.0.60833.0)

### .NET Framework Runtime v3.5 SP1

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-net35.png)](https://www.maravento.com/p/winexternal.html)

- .NET Framework v3.5 SP1 Standalone Installation Package for Windows 10/11 (x64 22H2 or Later - EN/SP) / Paquete independiente de instalación de .NET Framework v3.5 SP1 para Windows 10/11 (x64 22H2 o Superior - EN/ES)

#### Important About .NET Framework Runtime v3.5 SP1

- Backward compatibility with previous versions of Windows 10/11 21H2 or Windows Server versions is not guaranteed / No se garantiza retro-compatibilidad con versiones anteriores de Windows 10/11 21H2 o versiones Windows Server
- Only OS English/Spanish / Solo SO Inglés/Español
- Installation can fail for many reasons. In this case, unzip `WinExternal.exe` on your operating system drive (e.g.: `c:\`), go to `WinExternal\NET35\alternative` and run the `Install .NET Framework 3.5 via DISM.cmd` script with administrative privileges (ISO image required). For more information see `WinExternal\NET35\alternative\readme.txt` / La instalación puede fallar por muchas causas. En este caso descomprima `WinExternal.exe` en la unidad de su sistema operativo (ej: `c:\`), acceda a `WinExternal\NET35\alternative` y ejecute el script `Install .NET Framework 3.5 via DISM.cmd` con privilegios administrativos (requiere imagen ISO). Para mayor información consulte `WinExternal\NET35\alternative\readme.txt`

### .NET Framework Runtime v4.8.1

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-net481.png)](https://www.maravento.com/p/winexternal.html)

- .NET Framework Runtime v4.8.1 Standalone Installation Package for Windows 10/11 (20H2 or Later - EN/SP) (4.8.9037.6) / Paquete independiente de instalación de .NET Framework Runtime v4.8.1 para Windows 10/11 (20H2 o Superior - EN/ES) (4.8.9037.6)

#### Important About .NET Framework Runtime v4.8.1

- Includes native support for Arm64, Accessible Tooltips, Windows Forms – Accessibility Improvements. For more information, check: / Incluye soporte nativo para Arm64, información sobre herramientas accesible, Windows Forms - Mejoras de accesibilidad. Para mayor información, consulte: [Release Notes](https://github.com/microsoft/dotnet/blob/master/releases/net481/README.md)
- Backward compatibility with previous versions of Windows 10/11 20H2 is not guaranteed / No se garantiza retro-compatibilidad con versiones anteriores de Windows 10/11 20H2
- Only use this installer in case traditional methods fail (WSUS, SCCM or similar) / Solo use este instalador en caso de fallo en los métodos tradicionales (WSUS, SCCM o similar)

### .NET Desktop Runtime

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-netruntime.png)](https://www.maravento.com/p/winexternal.html)

- .NET Desktop Runtime x64 v7.0.8 (Standard Term Support - STS)
- .NET Desktop Runtime x64 v6.0.19 (Long Term Support - LTS)

check with: / verifique con:

```bash
dotnet --info
```

### WebView2 Runtime

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-webview2.png)](https://www.maravento.com/p/winexternal.html)

- WebView2 Runtime Installer x64 v114.0.1823.67

### Legacy Pack for Windows 7

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-legacy.png)](https://www.maravento.com/p/winexternal.html)

- Directx End-User Runtimes 9.29.1974.1 (June 2010)
- .NetFramework Runtime v4.8 (4.8.4115.0 ENU / 4.8.3761.0 ESN)
- XNA Framework Redistributable v4.0 Refresh (3.0.5419.0)

## IMPORTANT

---

### Shared or Included Packages

- [.NET Framework Runtime v4.8 is included in Windows 10 May 2019 and later / .NET Framework Runtime v4.8 se incluye en Windows 10 Mayo 2019 y posteriores](https://docs.microsoft.com/en-us/dotnet/framework/install/on-windows-10#net-framework-48)
- [Since Visual Studio 2015 share the same redistributable files / Desde Visual Studio 2015 comparten los mismos archivos redistribuibles](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)

### End-of-Life (EOL) / End-of-Support (EOS)

The following installers no longer run on WinExternal: / Los siguientes instaladores ya no se ejecutan en WinExternal:

- [Silverlight](https://support.microsoft.com/en-us/windows/silverlight-end-of-support-0a3be3c7-bead-e203-2dfd-74f0a64f1788) (EOS October 12, 2021)
- [Visual J# Version 2.0 Redistributable Package SE](https://docs.microsoft.com/en-us/lifecycle/products/microsoft-visual-j-version-20-redistributable-package) ([x86](http://web.archive.org/web/20201023224856/https://www.microsoft.com/en-us/download/details.aspx?id=18084) [x64](http://web.archive.org/web/20200812110243/https://www.microsoft.com/en-us/download/details.aspx?id=15468)) (EOS Jul 12, 2016)
- [Visual Studio 2010 F# 2.0](http://web.archive.org/web/20200721134946/https://www.microsoft.com/en-us/download/details.aspx?id=15834) (EOS Jul 14, 2020)

## USED TOOLS

---

- [7zSFX Builder](https://sourceforge.net/projects/s-zipsfxbuilder/)
- [iconarchive](http://www.iconarchive.com/show/fs-icons-by-franksouza183/Places-folder-windows-icon.html)
- [icon-icons](https://icon-icons.com/icon/dot-net-original-logo/146546)
- [Microsoft DirectX End-User Runtime](https://www.microsoft.com/en-us/download/details.aspx?id=8109)
- [Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)
- [Microsoft .NET Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet)
- [Microsoft NetFramework Runtime](https://dotnet.microsoft.com/download/dotnet-framework)
- [Microsoft Visual C++ Runtime](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)
- [Microsoft XNA Framework Redistributable](https://www.microsoft.com/en-us/download/details.aspx?id=27598)
- [Resource Turner](http://www.restuner.com/)
- [vcredist](https://github.com/abbodi1406/vcredist/releases)
- [WinZenity](https://github.com/maravento/winzenity)

## CONTRIBUTIONS

---

We thank all those who contributed to this project / Agradecemos a todos los que han contribuido con este proyecto

## DONATE

---

BTC: 3M84UKpz8AwwPADiYGQjT9spPKCvbqm4Bc

## LICENCES

---

[![GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl.txt)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

© 2023 [Maravento Studio](https://www.maravento.com)

## DISCLAIMER

---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
