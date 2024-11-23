# [WinExternal](https://www.maravento.com/p/winexternal.html)

<!-- markdownlint-disable MD033 -->

[![status-stable](https://img.shields.io/badge/status-stable-green.svg)](https://github.com/winexternal)
[![last commit](https://img.shields.io/github/last-commit/maravento/winexternal)](https://github.com/maravento/winexternal)
[![Twitter Follow](https://img.shields.io/twitter/follow/maraventostudio.svg?style=social)](https://twitter.com/maraventostudio)

<table align="center">
  <tr>
    <td align="center">
      <a href="README.md">English</a> | <span>Español</span>
    </td>
  </tr>
</table>

**WinExternal** es un proyecto que recopila varios instaladores fuera de línea de Microsoft para Windows, en un lanzador desatendido y silencioso.

## DATA SHEET

---

|File|OS|Size|
| :---: | :---: | :---: |
|[WinExternal.exe (.zip)](https://mega.nz/file/DRUCARwQ#9F8wHvg1R3cE9HlMH3AsTN3X0L0DplnXfjjH8eMaWto)|Windows 7/10/11 x86 x64|997.4 MB|

## HOW TO USE

---

Desactive su Antivirus, Antimalware, SmartScreen o cualquier otra solución de seguridad en su Sistema Operativo, cierre todas las ventanas y verifique la fecha y hora de su PC sea la correcta. Descargue WinExternal.exe (.zip), descomprimirlo en el escritorio, ejecutarlo con doble clic (acepte la ejecución con privilegios) y siga las instrucciones en pantalla.

## SELECTOR

---

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-selector.png)](https://www.maravento.com/p/winexternal.html)

WinExternal contiene paquetes independientes. Seleccione el de su preferencia.

### OS

Todos los paquetes son compatibles únicamente con Windows 10/11 x64, excepto [Legacy](https://github.com/maravento/winexternal#microsoft-legacy), que es compatible solo con Windows 7 x86 y cuyos componentes han alcanzado el End-of-Life (EOL) / End-of-Support (EOS). No se garantiza retro-compatibilidad con versiones anteriores de Windows 10/11 22H2 o versiones Windows Server. Si su SO no es compatible con el componente que ha seleccionado, saldrá la siguiente ventana:

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-abort.png)](https://www.maravento.com/p/winexternal.html)

### Microsoft Visual C++ Redistributable Runtimes

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-visualc.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Visual Basic/C++ Runtime x86 - 1.1.0
- Microsoft Visual C++ 2005 Redistributable x86 x64 - 8.0.61187
- Microsoft Visual C++ 2008 Redistributable x86 x64 - 9.30729.7523
- Microsoft Visual C++ 2010 Redistributable x86 x64 - 10.0.40219
- Microsoft Visual C++ 2012 Redistributable x86 x64 (Additional and Minimum Runtime) - 11.0.61135
- Microsoft Visual C++ 2013 Redistributable x86 x64 (Additional and Minimum Runtime) - 12.0.40664
- Microsoft Visual C++ 2022 Redistributable x86 x64 (Additional and Minimum Runtime) - 14.42.34433

#### Add-On

- Microsoft Visual Studio 2010 Tools for Office Runtime x64 - 10.0.60917.0
- Microsoft Visual Studio Tools for Applications 2022 x86 - 17.0.33529

### Microsoft .NET Framework Runtime v3.5 SP1

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-net35.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET Framework v3.5 SP1 Standalone Installation Package (for Windows 10 22H2 x64 and Windows 11 24H2 x64)

#### Important About Microsoft .NET Framework Runtime v3.5 SP1

- La instalación puede fallar por muchas causas. En este caso descomprima `WinExternal.exe` en la unidad de su sistema operativo (ej: `c:\`), acceda a `WinExternal\NET35\alternative` y ejecute el script `Install .NET Framework 3.5 via DISM.cmd` con privilegios administrativos (requiere imagen ISO). Para mayor información consulte `WinExternal\NET35\alternative\readme.txt`
- Solo SO Inglés/Español

### Microsoft .NET Framework Runtime v4.8.1

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-net481.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET Framework Runtime 4.8.1 Standalone Installation Package (for Windows 10/11 EN/SP for 20H2 or Later) - 4.8.9037.6

#### Important About Microsoft .NET Framework Runtime v4.8.1

- Incluye soporte nativo para Arm64, información sobre herramientas accesible, Windows Forms - Mejoras de accesibilidad. Para mayor información, consulte: [Release Notes](https://github.com/microsoft/dotnet/blob/master/releases/net481/README.md)
- Solo use este instalador en caso de fallo en los métodos tradicionales (WSUS, SCCM o similar)

### Microsoft .NET Desktop Runtime

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-netruntime.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft .NET 9.0.0 Desktop Runtime x64 LTS (Active)
- Microsoft .NET 8.0.11 Desktop Runtime x64 LTS (Active)
- Microsoft .NET 6.0.36 Desktop Runtime x64 LTS (End of Support EOS)

check with: / verifique con:

```bash
dotnet --info
```

### Microsoft Edge

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-edge.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Edge for Business x64 - 131.0.2903.63
- Microsoft Edge WebView2 Evergreen Standalone Installer x64 - 131.0.2903.63

#### Important About Edge

Edge y WebView2 ahora vienen instalados en la mayoría de los dispositivos con Windows 10 o superior, se actualizan automáticamente y se integran como un componente esencial del sistema operativo, por tanto no admiten desinstalación por métodos tradicionales. Si selecciona esta opción en el menú selector de WinExternal, solo instalará estos componentes, en caso de que no existan en su sistema operativo. Verifique [Feedback](https://github.com/MicrosoftEdge/WebView2Feedback/issues/3780).

### Microsoft Legacy

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/winexternal-legacy.png)](https://www.maravento.com/p/winexternal.html)

- Microsoft Directx End-User Runtimes - 9.29.1974.1 (EOS Jun 2010)
- Microsoft .NET Framework Runtime v4.8 - 4.8.4115.0 ENU | 4.8.3761.0 ESN
- Microsoft Visual J# Version 2.0 Redistributable Package - Second Edition (x86 x64) (EOS Jul 2016)
- Microsoft Visual Studio 2010 F# 2.0 SP1 (EOS Jul 2020)
- Microsoft XNA Framework Redistributable v4.0 - 4.0.20823.0

### Telemetry

WinExternal envía información al desarrollador, únicamente con el propósito de verificar que la instalación se haya completado de manera exitosa. Esta información se utiliza exclusivamente para fines estadísticos y de mejora del instalador, sin recopilar datos personales ni comprometer la privacidad del usuario. Ejemplo:

```bash
Package Installation
Hostname=DESKTOP-AJ4JSC8
User=Usuario
Date=mié. 13/11/2024 Time= 6:44:17,39
Status=Installed
Package: WinExternal
```


## IMPORTANT

---

- [.NET Framework Runtime v4.8 se incluye en Windows 10 Mayo 2019 y posteriores](https://docs.microsoft.com/en-us/dotnet/framework/install/on-windows-10#net-framework-48)
- [Microsoft Silverlight ya no se ejecuta en WinExternal (EOS Oct 2021)](https://support.microsoft.com/en-us/windows/silverlight-end-of-support-0a3be3c7-bead-e203-2dfd-74f0a64f1788)
- [Microsoft XML Core Services (MSXML) ya no se ejecuta en WinExternal (EOS Oct 2021)](https://learn.microsoft.com/en-us/lifecycle/products/microsoft-xml-core-services-40)
- [Desde Visual Studio 2015 comparten los mismos archivos redistribuibles](https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)
- [Microsoft Visual Studio Tools for Application 2019 - EOS](https://www.microsoft.com/en-us/download/details.aspx?id=58317)

## USED TOOLS

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

Agradecemos a todos los que han contribuido con este proyecto

## SPONSOR THIS PROJECT

---

[![Image](https://raw.githubusercontent.com/maravento/winexternal/master/img/maravento-paypal.png)](https://paypal.me/maravento)

## LICENSES

---

[![GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl.txt)
[![CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC_BY--NC--ND_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.en)

## DISCLAIMER

---

EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O IMPLÍCITA, INCLUYENDO, ENTRE OTRAS, LAS GARANTÍAS DE COMERCIABILIDAD, IDONEIDAD PARA UN PROPÓSITO PARTICULAR Y NO INFRACCIÓN. EN NINGÚN CASO LOS AUTORES O TITULARES DE LOS DERECHOS DE AUTOR SERÁN RESPONSABLES DE NINGUNA RECLAMACIÓN, DAÑO U OTRA RESPONSABILIDAD, YA SEA EN UNA ACCIÓN CONTRACTUAL, EXTRACONTRACTUAL O DE OTRO MODO, QUE SURJA DE, A PARTIR DE O EN CONEXIÓN CON EL SOFTWARE O EL USO U OTRAS OPERACIONES EN EL SOFTWARE.
