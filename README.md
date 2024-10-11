# [WinExternal](https://www.maravento.com/p/winexternal.html)

[![status-stable](https://img.shields.io/badge/status-stable-green.svg)](https://github.com/winexternal)
[![last commit](https://img.shields.io/github/last-commit/maravento/winexternal)](https://github.com/maravento/winexternal)
[![Twitter Follow](https://img.shields.io/twitter/follow/maraventostudio.svg?style=social)](https://twitter.com/maraventostudio)

**WinExternal** is a project that compiles several Microsoft offline installers for Windows, into one silent, unattended launcher.

**WinExternal** es un proyecto que recopila varios instaladores fuera de línea de Microsoft para Windows, en un lanzador desatendido y silencioso.

## DATA SHEET

---

|File|OS|Size|
| :---: | :---: | :---: |
|[WinExternal.exe (.zip)](https://mega.nz/file/GIUlXL7K#ILfebfXyRDRNQVpEBkMWFlx2J6f8iPQjpyBVclzycs8)|Windows 7/8/10/11 x86 x64|934,7 MB|

## HOW TO USE

---

Disable your Antivirus, Antimalware, SmartScreen or any other security solution in your Operating System, close all windows and check the date and time of your PC is correct. Download WinExternal.exe (.zip), unzip it to your desktop, execute it with double click (accept privileged execution) and follow the instructions on the screen

Desactive su Antivirus, Antimalware, SmartScreen o cualquier otra solución de seguridad en su Sistema Operativo, cierre todas las ventanas y verifique la fecha y hora de su PC sea la correcta. Descargue WinExternal.exe (.zip), descomprimirlo en el escritorio, ejecutarlo con doble clic (acepte la ejecución con privilegios) y siga las instrucciones en pantalla

## SELECTOR

---

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-selector.png)](https://www.maravento.com/p/winexternal.html)

WinExternal contains standalone packages. Select the one of your preference / WinExternal contiene paquetes independientes. Seleccione el de su preferencia

### Microsoft Visual C++ Redistributable Runtimes

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-visualc.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Visual Basic/C++ Runtime x86 - 1.1.0
- Microsoft Visual C++ 2005 Redistributable x86 x64 - 8.0.61187
- Microsoft Visual C++ 2008 Redistributable x86 x64 - 9.30729.7523
- Microsoft Visual C++ 2010 Redistributable x86 x64 - 10.0.40219
- Microsoft Visual C++ 2012 Redistributable x86 x64 (Additional and Minimum Runtime) - 11.0.61135
- Microsoft Visual C++ 2013 Redistributable x86 x64 (Additional and Minimum Runtime) - 12.0.40664
- Microsoft Visual C++ 2022 Redistributable x86 x64 (Additional and Minimum Runtime) - 14.42.34430

#### Add-on

- Microsoft Visual Studio 2010 Tools for Office Runtime x64 - 10.0.60917.0
- Microsoft Visual Studio Tools for Applications 2022 x86 - 17.0.33529

### Microsoft .NET Framework Runtime v3.5 SP1

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-net35.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET Framework v3.5 SP1 Standalone Installation Package (for Windows 10/11 x64 EN/SP 22H2 or Later)

#### Important About Microsoft .NET Framework Runtime v3.5 SP1

- Backward compatibility with previous versions of Windows 10/11 21H2 or Windows Server versions is not guaranteed / No se garantiza retro-compatibilidad con versiones anteriores de Windows 10/11 21H2 o versiones Windows Server
- Installation can fail for many reasons. In this case, unzip `WinExternal.exe` on your operating system drive (e.g.: `c:\`), go to `WinExternal\NET35\alternative` and run the `Install .NET Framework 3.5 via DISM.cmd` script with administrative privileges (ISO image required). For more information see `WinExternal\NET35\alternative\readme.txt` / La instalación puede fallar por muchas causas. En este caso descomprima `WinExternal.exe` en la unidad de su sistema operativo (ej: `c:\`), acceda a `WinExternal\NET35\alternative` y ejecute el script `Install .NET Framework 3.5 via DISM.cmd` con privilegios administrativos (requiere imagen ISO). Para mayor información consulte `WinExternal\NET35\alternative\readme.txt`
- Only OS English/Spanish / Solo SO Inglés/Español

### Microsoft .NET Framework Runtime v4.8.1

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-net481.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET Framework Runtime 4.8.1 Standalone Installation Package (for Windows 10/11 EN/SP for 20H2 or Later) - 4.8.9037.6

#### Important About Microsoft .NET Framework Runtime v4.8.1

- Backward compatibility with previous versions of Windows 10/11 20H2 is not guaranteed / No se garantiza retro-compatibilidad con versiones anteriores de Windows 10/11 20H2
- Includes native support for Arm64, Accessible Tooltips, Windows Forms – Accessibility Improvements. For more information, check: / Incluye soporte nativo para Arm64, información sobre herramientas accesible, Windows Forms - Mejoras de accesibilidad. Para mayor información, consulte: [Release Notes](https://github.com/microsoft/dotnet/blob/master/releases/net481/README.md)
- Only use this installer in case traditional methods fail (WSUS, SCCM or similar) / Solo use este instalador en caso de fallo en los métodos tradicionales (WSUS, SCCM o similar)

### Microsoft .NET Desktop Runtime

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-netruntime.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET Desktop Runtime x64 LTS (Active) - 8.0.10
- Microsoft .NET Desktop Runtime x64 LTS (Maintenance) - 6.0.35

check with: / verifique con:

```bash
dotnet --info
```

### Microsoft Edge

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-edge.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Edge for Business x64 - 129.0.2792.89
- Microsoft Edge WebView2 Evergreen Standalone Installer x64 - 129.0.2792.89

### Microsoft Legacy

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-legacy.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Directx End-User Runtimes - 9.29.1974.1 (EOS Jun 2010)
- Microsoft .NET Framework Runtime v4.8 - 4.8.4115.0 ENU | 4.8.3761.0 ESN
- Microsoft Visual J# Version 2.0 Redistributable Package - Second Edition (x86 x64) (EOS Jul 2016)
- Microsoft Visual Studio 2010 F# 2.0 SP1 (EOS Jul 2020)
- Microsoft XNA Framework Redistributable v4.0 - 4.0.20823.0

## IMPORTANT

---

- Legacy only supports Windows 7 or earlier versions, and some packages have: /  Legacy solo admite Windows 7 o versiones anteriores y algunos paquetes tienen: **End-of-Life (EOL) / End-of-Support (EOS)** status
- [Microsoft .NET Framework Runtime v4.8 is included in Windows 10 May 2019 and later / .NET Framework Runtime v4.8 se incluye en Windows 10 Mayo 2019 y posteriores](https://docs.microsoft.com/en-us/dotnet/framework/install/on-windows-10#net-framework-48)
- [Microsoft Silverlight no longer run on WinExternal / ya no se ejecuta en WinExternal (EOS Oct 2021)](https://support.microsoft.com/en-us/windows/silverlight-end-of-support-0a3be3c7-bead-e203-2dfd-74f0a64f1788)
- [Microsoft XML Core Services (MSXML) no longer run on WinExternal / ya no se ejecuta en WinExternal (EOS Oct 2021)](https://learn.microsoft.com/en-us/lifecycle/products/microsoft-xml-core-services-40)
- [Since Microsoft Visual Studio 2015 share the same redistributable files / Desde Visual Studio 2015 comparten los mismos archivos redistribuibles](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)
- [Microsoft Visual Studio Tools for Application 2019 - EOS](https://www.microsoft.com/en-us/download/details.aspx?id=58317)

## USED TOOLS

---

- [7zSFX Builder](https://sourceforge.net/projects/s-zipsfxbuilder/)
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

## STARGAZERS

---

[![Stargazers](https://bytecrank.com/nastyox/reporoster/php/stargazersSVG.php?user=maravento&repo=winexternal)](https://github.com/maravento/winexternal/stargazers)

## CONTRIBUTIONS

---

We thank all those who contributed to this project / Agradecemos a todos los que han contribuido con este proyecto

## SPONSOR THIS PROJECT

---

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/maravento-paypal.png)](https://paypal.me/maravento)

## LICENSES

---

[![GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl.txt)
[![CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC_BY--NC--ND_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.en)

## DISCLAIMER

---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
