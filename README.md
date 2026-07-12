# [WinExternal](https://www.maravento.com/p/winexternal.html)

[![status-maintained](https://img.shields.io/badge/status-maintained-purple.svg)](https://github.com/winexternal)
[![last commit](https://img.shields.io/github/last-commit/maravento/winexternal)](https://github.com/maravento/winexternal)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/maravento/winexternal)
[![Twitter Follow](https://img.shields.io/twitter/follow/maraventostudio.svg?style=social)](https://twitter.com/maraventostudio)

<!-- markdownlint-disable MD033 -->

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      <b>WinExternal</b> is a project that compiles several Microsoft offline installers for Windows, into one silent, unattended launcher.
    </td>
    <td style="width: 50%; vertical-align: top;">
      <b>WinExternal</b> es un proyecto que recopila varios instaladores fuera de línea de Microsoft para Windows, en un lanzador desatendido y silencioso.
    </td>
  </tr>
</table>

## DATA SHEET

---

| File | OS | Size |
| :---: | :---: | :---: |
| [WinExternal.exe (.zip)](https://mega.nz/file/LMkghDaA#-0mNhefKPfPSmmBcH88vpQe6Eg3hfcDZfbOnlxFYmnA) | Windows 7/10/11 x86 x64 | 1.12 GB |

## HOW TO USE

---

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      Disable your Antivirus, Antimalware, SmartScreen or any other security solution in your Operating System, close all windows and check the date and time of your PC is correct. Download WinExternal.exe (.zip), unzip it to your desktop, execute it with double click (accept privileged execution) and follow the instructions on the screen.
    </td>
    <td style="width: 50%; vertical-align: top;">
      Desactive su Antivirus, Antimalware, SmartScreen o cualquier otra solución de seguridad en su Sistema Operativo, cierre todas las ventanas y verifique que la fecha y hora de su PC sea la correcta. Descargue WinExternal.exe (.zip), descomprímalo en el escritorio, ejecútelo con doble clic (acepte la ejecución con privilegios) y siga las instrucciones en pantalla.
    </td>
  </tr>
</table>

## SELECTOR

---

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-selector.png)](https://www.maravento.com/p/winexternal.html)

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      WinExternal contains standalone packages. Select the one of your preference.
    </td>
    <td style="width: 50%; vertical-align: top;">
      WinExternal contiene paquetes independientes. Seleccione el de su preferencia.
    </td>
  </tr>
</table>

### OS

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      All packages are supported on Windows 10/11 x64 only, except <a href="#microsoft-legacy">Legacy</a>, which is supported on Windows 7 x86 only and whose components have reached End-of-Life (EOL) / End-of-Support (EOS). Backward compatibility with previous versions of Windows 10/11 22H2 or Windows Server versions is not guaranteed. If your OS does not support the component you selected, the following window will appear:
    </td>
    <td style="width: 50%; vertical-align: top;">
      Todos los paquetes son compatibles únicamente con Windows 10/11 x64, excepto <a href="#microsoft-legacy">Legacy</a>, que es compatible solo con Windows 7 x86 y cuyos componentes han alcanzado el End-of-Life (EOL) / End-of-Support (EOS). No se garantiza retro-compatibilidad con versiones anteriores de Windows 10/11 22H2 o versiones Windows Server. Si su SO no es compatible con el componente que ha seleccionado, saldrá la siguiente ventana:
    </td>
  </tr>
</table>

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-abort.png)](https://www.maravento.com/p/winexternal.html)

### Microsoft Visual C++ Redistributable Runtimes

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-visualc.png)](https://www.maravento.com/p/winexternal.html)

#### VCRedist

- Microsoft Visual Basic/C++ Runtime x86 - 1.1.0 (EOS)
- Microsoft Visual C++ 2005 Redistributable x86 x64 - 8.0.61187 (EOS)
- Microsoft Visual C++ 2008 Redistributable x86 x64 - 9.30729.7523 (EOS)
- Microsoft Visual C++ 2010 Redistributable x86 x64 - 10.0.40219 (EOS)
- Microsoft Visual C++ 2012 Redistributable x86 x64 - 11.0.61135 (EOS)
- Microsoft Visual C++ 2013 Redistributable x86 x64 - 12.0.40664 (EOS)
- Microsoft Visual C++ 2026 Redistributable x86 x64 - 14.51.36247 (Active Support)

#### VSTO

- Microsoft Visual Studio 2010 Tools for Office Runtime x86 x64 - 10.0.609922 (EOS)

#### VSTA

- Microsoft Visual Studio Tools for Applications 2017 x86 x64 - 15.0.36010 (Active Support)
- Microsoft Visual Studio Tools for Applications 2019 x86 x64 - 16.0.35907 (Active Support)
- Microsoft Visual Studio Tools for Applications 2022 x86 x64 - 17.1.37110 (Active Support)

### Microsoft .NET Framework Runtime v3.5 SP1

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-net35.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET Framework v3.5 SP1 (for Windows 10/11 22H2 or Later) (Active Support)

#### Important About Microsoft .NET Framework Runtime v3.5 SP1

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      <ul>
        <li>Installation can fail for many reasons. In this case, unzip <code>WinExternal.exe</code> on your operating system drive (e.g.: <code>c:\</code>), go to <code>WinExternal\NET35\alternative</code> and run the <code>Install .NET Framework 3.5 via DISM.cmd</code> script with administrative privileges (ISO image required). For more information see <code>WinExternal\NET35\alternative\readme.txt</code>.</li>
        <li>Only OS English/Spanish</li>
      </ul>
    </td>
    <td style="width: 50%; vertical-align: top;">
      <ul>
        <li>La instalación puede fallar por muchas causas. En este caso descomprima <code>WinExternal.exe</code> en la unidad de su sistema operativo (ej: <code>c:\</code>), acceda a <code>WinExternal\NET35\alternative</code> y ejecute el script <code>Install .NET Framework 3.5 via DISM.cmd</code> con privilegios administrativos (requiere imagen ISO). Para mayor información consulte <code>WinExternal\NET35\alternative\readme.txt</code>.</li>
        <li>Solo SO Inglés/Español</li>
      </ul>
    </td>
  </tr>
</table>

### Microsoft .NET Framework Runtime v4.8.1

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-net481.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET Framework Runtime 4.8.1 - 4.8.9037.6 (for Windows 10/11 20H2 or Later) (Active Support)

#### Important About Microsoft .NET Framework Runtime v4.8.1

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      <ul>
        <li>Includes native support for Arm64, Accessible Tooltips, Windows Forms – Accessibility Improvements. For more information, check: <a href="https://github.com/microsoft/dotnet/blob/master/releases/net481/README.md" target="_blank">Release Notes</a></li>
        <li>Only use this installer in case traditional methods fail (WSUS, SCCM or similar).</li>
      </ul>
    </td>
    <td style="width: 50%; vertical-align: top;">
      <ul>
        <li>Incluye soporte nativo para Arm64, información sobre herramientas accesible, Windows Forms - Mejoras de accesibilidad. Para mayor información, consulte: <a href="https://github.com/microsoft/dotnet/blob/master/releases/net481/README.md" target="_blank">Release Notes</a></li>
        <li>Solo use este instalador en caso de fallo en los métodos tradicionales (WSUS, SCCM o similar).</li>
      </ul>
    </td>
  </tr>
</table>

### Microsoft .NET Desktop Runtime

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-netruntime.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET 6.0.36 Desktop Runtime x64 LTS (EOS)
- Microsoft .NET 8.0.28 Desktop Runtime x64 LTS (Active Support)
- Microsoft .NET 10.0.9 Desktop Runtime x64 LTS (Active Support)

check with / verifique con:

```bash
dotnet --info
```

### Microsoft Edge

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-edge.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Edge for Business x64 - 149.0.4022.98 (Active Support)
- Microsoft Edge WebView2 Evergreen Standalone Installer x64 - 149.0.4022.98 (Active Support)

#### Important About Edge

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      Edge and WebView2 are now pre-installed on most devices running Windows 10 or higher, are automatically updated, and are integrated as a core component of the operating system, so they do not support uninstallation by traditional methods. Selecting this option from the WinExternal selector menu will only install these components, if they do not exist on your operating system. Check <a href="https://github.com/MicrosoftEdge/WebView2Feedback/issues/3780" target="_blank">Feedback</a>.
    </td>
    <td style="width: 50%; vertical-align: top;">
      Edge y WebView2 ahora vienen instalados en la mayoría de los dispositivos con Windows 10 o superior, se actualizan automáticamente y se integran como un componente esencial del sistema operativo, por tanto no admiten desinstalación por métodos tradicionales. Si selecciona esta opción en el menú selector de WinExternal, solo instalará estos componentes en caso de que no existan en su sistema operativo. Verifique <a href="https://github.com/MicrosoftEdge/WebView2Feedback/issues/3780" target="_blank">Feedback</a>.
    </td>
  </tr>
</table>

### Microsoft Windows App Runtime SDK

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-sdk.png)](https://www.maravento.com/p/winexternal.html)

- Windows App SDK 2.2.0 Installer x64 (Active Support)

#### Important About Windows App Runtime SDK

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      Check version with:
    </td>
    <td style="width: 50%; vertical-align: top;">
      Comprobar versión con:
    </td>
  </tr>
</table>

```powershell
Get-AppxPackage -AllUsers *WindowsAppRuntime* | Select-Object Name, Version
```

### Microsoft Legacy

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-legacy.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Directx End-User Runtimes - 9.29.1974.1 (EOS)
- Microsoft .NET Framework Runtime v4.8 - 4.8.4115.0 ENU | 4.8.3761.0 ESN (Active Support)
- Microsoft Visual J# Version 2.0 Redistributable Package - Second Edition (x86 x64) (EOS)
- Microsoft Visual Studio 2010 F# 2.0 SP1 (EOS)
- Microsoft XNA Framework Redistributable v4.0 - 4.0.20823.0 (EOS)

### Telemetry

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      WinExternal sends information to the developer, only for the purpose of verifying that the installation has been completed successfully. This information is used exclusively for statistical purposes and to improve the installer, without collecting personal data or compromising user privacy. Example:
    </td>
    <td style="width: 50%; vertical-align: top;">
      WinExternal envía información al desarrollador, únicamente con el propósito de verificar que la instalación se haya completado de manera exitosa. Esta información se utiliza exclusivamente para fines estadísticos y de mejora del instalador, sin recopilar datos personales ni comprometer la privacidad del usuario. Ejemplo:
    </td>
  </tr>
</table>

```bash
Package Installation
Hostname=DESKTOP-AJ4JSC8
User=Usuario
Date=wed. 13/11/2024 Time= 6:44:17,39
Status=Installed
Package: WinExternal
```

### IMPORTANT

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      <ul>
        <li>Some WinExternal components have reached End-of-Life (EOL) / End-of-Support (EOS), however, they will continue to be offered, where indicated, for compatibility with essential applications.</li>
        <li><a href="https://docs.microsoft.com/en-us/dotnet/framework/install/on-windows-10#net-framework-48" target="_blank">Microsoft .NET Framework Runtime v4.8 is included in Windows 10 May 2019 and later</a></li>
        <li><a href="https://support.microsoft.com/en-us/windows/silverlight-end-of-support-0a3be3c7-bead-e203-2dfd-74f0a64f1788" target="_blank">Microsoft Silverlight no longer runs on WinExternal (End-of-Life (EOL) / End-of-Support (EOS) Oct 2021)</a></li>
        <li><a href="https://learn.microsoft.com/en-us/lifecycle/products/microsoft-xml-core-services-40" target="_blank">Microsoft XML Core Services (MSXML) no longer runs on WinExternal (End-of-Life (EOL) / End-of-Support (EOS) Oct 2021)</a></li>
        <li><a href="https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170" target="_blank">Since Microsoft Visual Studio 2015, versions share the same redistributable files</a></li>
      </ul>
    </td>
    <td style="width: 50%; vertical-align: top;">
      <ul>
        <li>Algunos componentes de WinExternal han alcanzado End-of-Life (EOL) / End-of-Support (EOS), sin embargo seguirán ofreciéndose, donde se indique, por compatibilidad con aplicaciones esenciales.</li>
        <li><a href="https://docs.microsoft.com/en-us/dotnet/framework/install/on-windows-10#net-framework-48" target="_blank">.NET Framework Runtime v4.8 se incluye en Windows 10 Mayo 2019 y posteriores</a></li>
        <li><a href="https://support.microsoft.com/en-us/windows/silverlight-end-of-support-0a3be3c7-bead-e203-2dfd-74f0a64f1788" target="_blank">Microsoft Silverlight ya no se ejecuta en WinExternal (End-of-Life (EOL) / End-of-Support (EOS) Oct 2021)</a></li>
        <li><a href="https://learn.microsoft.com/en-us/lifecycle/products/microsoft-xml-core-services-40" target="_blank">Microsoft XML Core Services (MSXML) ya no se ejecuta en WinExternal (End-of-Life (EOL) / End-of-Support (EOS) Oct 2021)</a></li>
        <li><a href="https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170" target="_blank">Desde Visual Studio 2015 comparten los mismos archivos redistribuibles</a></li>
      </ul>
    </td>
  </tr>
</table>

## PACKAGES AND TOOLS

---

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
- [Microsoft Visual Studio Tools for Application 2017](https://www.microsoft.com/en-us/download/details.aspx?id=56046)
- [Microsoft Visual Studio Tools for Application 2019](https://www.microsoft.com/en-us/download/details.aspx?id=58317)
- [Microsoft Visual Studio Tools for Application 2022](https://www.microsoft.com/en-us/download/details.aspx?id=105123)
- [Microsoft XNA Framework Redistributable](https://www.microsoft.com/en-us/download/details.aspx?id=27598)
- [RapidCRC Unicode](https://www.ov2.eu/programs/rapidcrc-unicode)
- [vcredist](https://gitlab.com/stdout12/vcredist/-/releases)
- [Windows App SDK](https://learn.microsoft.com/en-us/windows/apps/windows-app-sdk/downloads)
- [WinZenity](https://github.com/maravento/vault/tree/master/winzenity)

## NOTICE

---

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      <ul>
        <li>This project includes third-party components.</li>
        <li>Changes must be submitted via Issues. Pull requests are not accepted.</li>
      </ul>
    </td>
    <td style="width: 50%; vertical-align: top;">
      <ul>
        <li>Este proyecto incluye componentes de terceros.</li>
        <li>Los cambios deben proponerse mediante Issues. No se aceptan Pull Requests.</li>
      </ul>
    </td>
  </tr>
</table>

## STARGAZERS

---

[![Stargazers](https://bytecrank.com/nastyox/reporoster/php/stargazersSVG.php?user=maravento&repo=winexternal)](https://github.com/maravento/winexternal/stargazers)

## CONTRIBUTIONS

---

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      We thank all those who contributed to this project.
    </td>
    <td style="width: 50%; vertical-align: top;">
      Agradecemos a todos los que han contribuido con este proyecto.
    </td>
  </tr>
</table>

## SPONSOR THIS PROJECT

---

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/maravento-paypal.png)](https://paypal.me/maravento)

## PROJECT LICENSES

---

<table width="100%">
  <tr>
    <td style="width: 50%; vertical-align: top;">
      This project uses a dual-licensing model to balance software freedom with content protection:
    </td>
    <td style="width: 50%; vertical-align: top;">
      Este proyecto utiliza un modelo de licencia dual para equilibrar la libertad del software con la protección del contenido:
    </td>
  </tr>
</table>

| Content | Licensed Under |
|---|---|
|Scripts, Binaries, Infrastructure|[![GPL-3.0](https://img.shields.io/badge/Open_Core-GPLv3-blue.svg?style=for-the-badge&labelWidth=120&logoWidth=20)](https://www.gnu.org/licenses/gpl.txt)|
|RAG, Workers, Specialized Modules, Docs|[![CC](https://img.shields.io/badge/Core_Engine-CC_BY--NC--ND_4.0-lightgrey.svg?style=for-the-badge&labelWidth=120&logoWidth=20)](https://creativecommons.org/licenses/by-nc-nd/4.0/)|

## DISCLAIMER

---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
