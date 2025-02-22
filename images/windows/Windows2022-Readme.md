| Announcements |
|-|
| [[Ubuntu, Windows] Az Powershell module will be updated to v11.3.1 on March 18](https://github.com/actions/runner-images/issues/9445) |
| [[All OSes] Ruby versions <= 2.7.x will be removed on February, 26](https://github.com/actions/runner-images/issues/9327) |
| [[All OSes] Go 1.19.x will be removed and 1.21.x set as default on February, 26](https://github.com/actions/runner-images/issues/9326) |
***
# Windows Server 2022
- OS Version: 10.0.20348 Build 2322
- Image Version: 20240310.1.0

## Windows features
- Windows Subsystem for Linux (WSLv1): Enabled

## Installed Software

### Language and Runtime
- Bash 5.2.26(1)-release
- Go 1.21.8
- Julia 1.10.2
- Kotlin 1.9.23
- LLVM 16.0.6
- Node 18.18.2
- Perl 5.32.1
- PHP 8.3.3
- Python 3.9.13
- Ruby 3.0.6p216

### Package Management
- Chocolatey 2.2.2
- Composer 2.7.1
- Helm 3.14.1
- Miniconda 24.1.2 (pre-installed on the image but not added to PATH)
- NPM 9.8.1
- NuGet 6.9.1.3
- pip 24.0 (python 3.9)
- Pipx 1.4.3
- RubyGems 3.2.33
- Vcpkg (build from commit 0719a7138)
- Yarn 1.22.22

#### Environment variables
| Name                    | Value        |
| ----------------------- | ------------ |
| VCPKG_INSTALLATION_ROOT | C:\vcpkg     |
| CONDA                   | C:\Miniconda |

### Project Management
- Ant 1.10.14
- Gradle 8.6
- Maven 3.8.7
- sbt 1.9.9

### Tools
- 7zip 23.01
- aria2 1.37.0
- azcopy 10.23.0
- Bazel 7.0.2
- Bazelisk 1.19.0
- Bicep 0.25.53
- Cabal 3.10.2.1
- CMake 3.28.3
- CodeQL Action Bundle 2.16.3
- Docker 24.0.7
- Docker Compose v1 1.29.2
- Docker Compose v2 2.23.3
- Docker-wincred 0.8.1
- ghc 9.8.2
- Git 2.44.0.windows.1
- Git LFS 3.4.1
- ImageMagick 7.1.1-29
- InnoSetup 6.2.2
- jq 1.7.1
- Kind 0.22.0
- Kubectl 1.29.1
- Mercurial 5.0
- gcc 12.2.0
- gdb 11.2
- GNU Binutils 2.39
- Newman 6.1.1
- NSIS 3.09
- OpenSSL 1.1.1w
- Packer 1.10.0
- Pulumi 3.109.0
- R 4.3.2
- Service Fabric SDK 9.1.1436.9590
- Stack 2.15.3
- Subversion (SVN) 1.14.2
- Swig 4.1.1
- VSWhere 3.1.7
- WinAppDriver 1.2.2009.02003
- WiX Toolset 3.14.0.8606
- yamllint 1.35.1
- zstd 1.5.5

### CLI Tools
- Alibaba Cloud CLI 3.0.199
- AWS CLI 2.15.27
- AWS SAM CLI 1.111.0
- AWS Session Manager CLI 1.2.553.0
- Azure CLI 2.58.0
- Azure DevOps CLI extension 1.0.0
- GitHub CLI 2.45.0

### Rust Tools
- Cargo 1.76.0
- Rust 1.76.0
- Rustdoc 1.76.0
- Rustup 1.26.0

#### Packages
- bindgen 0.69.4
- cargo-audit 0.20.0
- cargo-outdated 0.15.0
- cbindgen 0.26.0
- Clippy 0.1.76
- Rustfmt 1.7.0

### Browsers and Drivers
- Google Chrome 122.0.6261.112
- Chrome Driver 122.0.6261.111
- Microsoft Edge 122.0.2365.80
- Microsoft Edge Driver 122.0.2365.80
- Mozilla Firefox 123.0.1
- Gecko Driver 0.34.0
- IE Driver 4.14.0.0
- Selenium server 4.18.0

#### Environment variables
| Name              | Value                              |
| ----------------- | ---------------------------------- |
| CHROMEWEBDRIVER   | C:\SeleniumWebDrivers\ChromeDriver |
| EDGEWEBDRIVER     | C:\SeleniumWebDrivers\EdgeDriver   |
| GECKOWEBDRIVER    | C:\SeleniumWebDrivers\GeckoDriver  |
| SELENIUM_JAR_PATH | C:\selenium\selenium-server.jar    |

### Java
| Version             | Environment Variable |
| ------------------- | -------------------- |
| 8.0.402+6 (default) | JAVA_HOME_8_X64      |
| 11.0.22+7           | JAVA_HOME_11_X64     |
| 17.0.10+7           | JAVA_HOME_17_X64     |
| 21.0.2+13.0         | JAVA_HOME_21_X64     |

### Shells
| Name          | Target                            |
| ------------- | --------------------------------- |
| gitbash.exe   | C:\Program Files\Git\bin\bash.exe |
| msys2bash.cmd | C:\msys64\usr\bin\bash.exe        |
| wslbash.exe   | C:\Windows\System32\bash.exe      |

### MSYS2
- Pacman 6.0.2

#### Notes
```
Location: C:\msys64

Note: MSYS2 is pre-installed on image but not added to PATH.
```

### Cached Tools

#### Go
- 1.20.14
- 1.21.8
- 1.22.1

#### Node.js
- 16.20.2
- 18.19.1
- 20.11.1

#### Python
- 3.7.9
- 3.8.10
- 3.9.13
- 3.10.11
- 3.11.8
- 3.12.2

#### PyPy
- 2.7.18 [PyPy 7.3.15]
- 3.7.13 [PyPy 7.3.9]
- 3.8.16 [PyPy 7.3.11]
- 3.9.18 [PyPy 7.3.15]
- 3.10.13 [PyPy 7.3.15]

#### Ruby
- 3.0.6
- 3.1.4

### Databases

#### PostgreSQL
| Property             | Value                                                                                                                                |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| ServiceName          | postgresql-x64-14                                                                                                                    |
| Version              | 14.11                                                                                                                                |
| ServiceStatus        | Stopped                                                                                                                              |
| ServiceStartType     | Disabled                                                                                                                             |
| EnvironmentVariables | PGBIN=C:\Program Files\PostgreSQL\14\bin <br> PGDATA=C:\Program Files\PostgreSQL\14\data <br> PGROOT=C:\Program Files\PostgreSQL\14  |
| Path                 | C:\Program Files\PostgreSQL\14                                                                                                       |
| UserName             | postgres                                                                                                                             |
| Password             | root                                                                                                                                 |

#### MongoDB
| Version  | ServiceName | ServiceStatus | ServiceStartType |
| -------- | ----------- | ------------- | ---------------- |
| 5.0.25.0 | MongoDB     | Stopped       | Disabled         |

### Database tools
- Azure CosmosDb Emulator 2.14.16.0
- DacFx 162.2.111.2
- MySQL 8.0.36.0
- SQL OLEDB Driver 18.6.7.0
- SQLPS 1.0

### Web Servers
| Name   | Version | ConfigFile                            | ServiceName | ServiceStatus | ListenPort |
| ------ | ------- | ------------------------------------- | ----------- | ------------- | ---------- |
| Apache | 2.4.55  | C:\tools\Apache24\conf\httpd.conf     | Apache      | Stopped       | 80         |
| Nginx  | 1.25.4  | C:\tools\nginx-1.25.4\conf\nginx.conf | nginx       | Stopped       | 80         |

### Visual Studio Enterprise 2022
| Name                          | Version        | Path                                                     |
| ----------------------------- | -------------- | -------------------------------------------------------- |
| Visual Studio Enterprise 2022 | 17.9.34622.214 | C:\Program Files\Microsoft Visual Studio\2022\Enterprise |

#### Workloads, components and extensions
| Package                                                                   | Version         |
| ------------------------------------------------------------------------- | --------------- |
| android                                                                   | 34.0.52.0       |
| Component.Android.Emulator.MDD                                            | 17.9.34511.75   |
| Component.Android.NDK.R23C                                                | 17.9.34511.75   |
| Component.Android.SDK.MAUI                                                | 17.9.34511.75   |
| Component.Dotfuscator                                                     | 17.9.34511.75   |
| Component.HAXM.Private                                                    | 17.9.34511.75   |
| Component.Linux.CMake                                                     | 17.9.34511.75   |
| Component.Linux.RemoteFileExplorer                                        | 17.9.34511.75   |
| Component.MDD.Android                                                     | 17.9.34511.75   |
| Component.MDD.Linux                                                       | 17.9.34511.75   |
| Component.MDD.Linux.GCC.arm                                               | 17.9.34511.75   |
| Component.Microsoft.VisualStudio.LiveShare.2022                           | 1.0.5898        |
| Component.Microsoft.VisualStudio.RazorExtension                           | 17.9.34511.75   |
| Component.Microsoft.VisualStudio.Tools.Applications.amd64                 | 17.0.33617.0    |
| Component.Microsoft.VisualStudio.Web.AzureFunctions                       | 17.9.34511.75   |
| Component.Microsoft.Web.LibraryManager                                    | 17.9.34511.75   |
| Component.Microsoft.WebTools.BrowserLink.WebLivePreview                   | 17.9.2.55198    |
| Component.Microsoft.Windows.DriverKit                                     | 10.0.22621.0    |
| Component.OpenJDK                                                         | 17.9.34511.75   |
| Component.UnityEngine.x64                                                 | 17.9.34511.75   |
| Component.Unreal                                                          | 17.9.34511.75   |
| Component.Unreal.Android                                                  | 17.9.34511.75   |
| Component.Unreal.Ide                                                      | 17.9.34511.75   |
| Component.VSInstallerProjects2022                                         | 2.0.1           |
| Component.WixToolset.VisualStudioExtension.Dev17                          | 1.0.0.22        |
| Component.WixToolset.VisualStudioExtension.Schemas3                       | 1.0.0.22        |
| Component.Xamarin                                                         | 17.9.34511.75   |
| Component.Xamarin.RemotedSimulator                                        | 17.9.34511.75   |
| ios                                                                       | 17.2.8004.0     |
| maccatalyst                                                               | 17.2.8004.0     |
| maui.blazor                                                               | 8.0.6.0         |
| maui.core                                                                 | 8.0.6.0         |
| maui.windows                                                              | 8.0.6.0         |
| Microsoft.Component.Azure.DataLake.Tools                                  | 17.9.34511.75   |
| Microsoft.Component.ClickOnce                                             | 17.9.34511.75   |
| Microsoft.Component.CodeAnalysis.SDK                                      | 17.9.34511.75   |
| Microsoft.Component.MSBuild                                               | 17.9.34511.75   |
| Microsoft.Component.NetFX.Native                                          | 17.9.34511.75   |
| Microsoft.Component.PythonTools                                           | 17.9.34511.75   |
| Microsoft.Component.PythonTools.Web                                       | 17.9.34511.75   |
| Microsoft.Component.VC.Runtime.UCRTSDK                                    | 17.9.34511.75   |
| Microsoft.ComponentGroup.Blend                                            | 17.9.34511.75   |
| Microsoft.ComponentGroup.ClickOnce.Publish                                | 17.9.34511.75   |
| Microsoft.Net.Component.4.5.2.TargetingPack                               | 17.9.34511.75   |
| Microsoft.Net.Component.4.6.2.TargetingPack                               | 17.9.34511.75   |
| Microsoft.Net.Component.4.6.TargetingPack                                 | 17.9.34511.75   |
| Microsoft.Net.Component.4.7.1.TargetingPack                               | 17.9.34511.75   |
| Microsoft.Net.Component.4.7.2.TargetingPack                               | 17.9.34511.75   |
| Microsoft.Net.Component.4.7.TargetingPack                                 | 17.9.34511.75   |
| Microsoft.Net.Component.4.8.1.SDK                                         | 17.9.34511.75   |
| Microsoft.Net.Component.4.8.1.TargetingPack                               | 17.9.34511.75   |
| Microsoft.Net.Component.4.8.SDK                                           | 17.9.34511.75   |
| Microsoft.Net.Component.4.8.TargetingPack                                 | 17.9.34511.75   |
| Microsoft.Net.ComponentGroup.4.8.DeveloperTools                           | 17.9.34511.75   |
| Microsoft.Net.ComponentGroup.DevelopmentPrerequisites                     | 17.9.34511.75   |
| Microsoft.Net.ComponentGroup.TargetingPacks.Common                        | 17.9.34511.75   |
| microsoft.net.runtime.android                                             | 8.0.224.6711    |
| microsoft.net.runtime.android.aot                                         | 8.0.224.6711    |
| microsoft.net.runtime.android.aot.net7                                    | 8.0.224.6711    |
| microsoft.net.runtime.android.net7                                        | 8.0.224.6711    |
| microsoft.net.runtime.ios                                                 | 8.0.224.6711    |
| microsoft.net.runtime.ios.net7                                            | 8.0.224.6711    |
| microsoft.net.runtime.maccatalyst                                         | 8.0.224.6711    |
| microsoft.net.runtime.maccatalyst.net7                                    | 8.0.224.6711    |
| microsoft.net.runtime.mono.tooling                                        | 8.0.224.6711    |
| microsoft.net.runtime.mono.tooling.net7                                   | 8.0.224.6711    |
| microsoft.net.sdk.emscripten                                              | 8.0.10.6201     |
| Microsoft.NetCore.Component.DevelopmentTools                              | 17.9.34511.75   |
| Microsoft.NetCore.Component.Runtime.8.0                                   | 17.9.34606.255  |
| Microsoft.NetCore.Component.SDK                                           | 17.9.34606.255  |
| Microsoft.NetCore.Component.Web                                           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.AppInsights.Tools                        | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.AspNet                                   | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.AspNet45                                 | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Azure.AuthoringTools                     | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Azure.ClientLibs                         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Azure.Compute.Emulator                   | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Azure.Powershell                         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Azure.ResourceManager.Tools              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Azure.ServiceFabric.Tools                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Azure.Waverton                           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Azure.Waverton.BuildTools                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.ClassDesigner                            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.CodeMap                                  | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Common.Azure.Tools                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.CoreEditor                               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.CppBuildInsights                         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Debugger.JustInTime                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Debugger.Snapshot                        | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.DiagnosticTools                          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.DockerTools                              | 17.9.34518.88   |
| Microsoft.VisualStudio.Component.DotNetModelBuilder                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.DslTools                                 | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Embedded                                 | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.EntityFramework                          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.FSharp                                   | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.FSharp.Desktop                           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.FSharp.WebTemplates                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.GraphDocument                            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Graphics                                 | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Graphics.Tools                           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.HLSL                                     | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.IISExpress                               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.IntelliCode                              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.IntelliTrace.FrontEnd                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.JavaScript.Diagnostics                   | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.JavaScript.TypeScript                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.LinqToSql                                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.LiveUnitTesting                          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.ManagedDesktop.Core                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.ManagedDesktop.Prerequisites             | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Merq                                     | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.MonoDebugger                             | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.MSODBC.SQL                               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.MSSQL.CMDLnUtils                         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Node.Tools                               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.NuGet                                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.NuGet.BuildTools                         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.PortableLibrary                          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Roslyn.Compiler                          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Roslyn.LanguageServices                  | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.SecurityIssueAnalysis                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Sharepoint.Tools                         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.SQL.CLR                                  | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.SQL.DataSources                          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.SQL.LocalDB.Runtime                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.SQL.SSDT                                 | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.TeamOffice                               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.TestTools.CodedUITest                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.TestTools.WebLoadTest                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.TextTemplating                           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.TypeScript.TSServer                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Unity                                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.UWP.VC.ARM64                             | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.UWP.VC.ARM64EC                           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.ARM                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.ARM.Spectre               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.ARM64                     | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.ARM64.Spectre             | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.ATL                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.ATL.ARM                   | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.ATL.ARM.Spectre           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.ATL.ARM64                 | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.ATL.ARM64.Spectre         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.ATL.Spectre               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.MFC                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.MFC.ARM                   | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.MFC.ARM.Spectre           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.MFC.ARM64                 | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.MFC.ARM64.Spectre         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.MFC.Spectre               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.x86.x64                   | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.29.16.11.x86.x64.Spectre           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.ARM                        | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.ARM.Spectre                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.ARM64                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.ARM64.Spectre              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.ATL                        | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.ATL.ARM                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.ATL.ARM.Spectre            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.ATL.ARM64                  | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.ATL.ARM64.Spectre          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.ATL.Spectre                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.MFC                        | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.MFC.ARM                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.MFC.ARM.Spectre            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.MFC.ARM64                  | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.MFC.ARM64.Spectre          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.MFC.Spectre                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.x86.x64                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.38.17.8.x86.x64.Spectre            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.ARM                        | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.ARM.Spectre                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.ARM64                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.ARM64.Spectre              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.ATL                        | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.ATL.ARM                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.ATL.ARM.Spectre            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.ATL.ARM64                  | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.ATL.ARM64.Spectre          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.ATL.Spectre                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.MFC                        | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.MFC.ARM                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.MFC.ARM.Spectre            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.MFC.ARM64                  | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.MFC.ARM64.Spectre          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.MFC.Spectre                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.x86.x64                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.14.39.17.9.x86.x64.Spectre            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.ASAN                                  | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.ATL                                   | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.ATL.ARM                               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.ATL.ARM.Spectre                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.ATL.ARM64                             | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.ATL.ARM64.Spectre                     | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.ATL.Spectre                           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.ATLMFC                                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.ATLMFC.Spectre                        | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.CLI.Support                           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.CMake.Project                         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.CoreIde                               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.DiagnosticTools                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Llvm.Clang                            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Llvm.ClangToolset                     | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.MFC.ARM                               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.MFC.ARM.Spectre                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.MFC.ARM64                             | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.MFC.ARM64.Spectre                     | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Modules.x86.x64                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Redist.14.Latest                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Redist.MSM                            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Runtimes.ARM.Spectre                  | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Runtimes.ARM64.Spectre                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Runtimes.ARM64EC.Spectre              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Runtimes.x86.x64.Spectre              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.TestAdapterForBoostTest               | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.TestAdapterForGoogleTest              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Tools.ARM                             | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Tools.ARM64                           | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Tools.ARM64EC                         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.Tools.x86.x64                         | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.v141.ARM                              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.v141.ARM.Spectre                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.v141.ARM64                            | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.v141.ARM64.Spectre                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.v141.ATL                              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.v141.ATL.Spectre                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.v141.MFC                              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.v141.MFC.Spectre                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.v141.x86.x64                          | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VC.v141.x86.x64.Spectre                  | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Vcpkg                                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.VSSDK                                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Wcf.Tooling                              | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Web                                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.WebDeploy                                | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Windows10SDK                             | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Windows10SDK.19041                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Windows10SDK.20348                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Windows11SDK.22000                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Windows11SDK.22621                       | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Windows11Sdk.WindowsPerformanceToolkit   | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.Workflow                                 | 17.9.34511.75   |
| Microsoft.VisualStudio.Component.WslDebugging                             | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.ArchitectureTools.Native            | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Azure.CloudServices                 | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Azure.Prerequisites                 | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Azure.ResourceManager.Tools         | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.AzureFunctions                      | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Maui.All                            | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Maui.Android                        | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Maui.Blazor                         | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Maui.iOS                            | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Maui.MacCatalyst                    | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Maui.Shared                         | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Maui.Windows                        | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.MSIX.Packaging                      | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Core                  | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Llvm.Clang            | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.UWP.NetCoreAndStandard              | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.UWP.Support                         | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.UWP.VC.v142                         | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.UWP.Xamarin                         | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.VC.Tools.142.x86.x64                | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.VisualStudioExtension.Prerequisites | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Web                                 | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.Web.CloudTools                      | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions                  | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions.CMake            | 17.9.34511.75   |
| Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions.TemplateEngine   | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.Azure                                     | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.CoreEditor                                | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.Data                                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.DataScience                               | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.ManagedDesktop                            | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.ManagedGame                               | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.NativeCrossPlat                           | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.NativeDesktop                             | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.NativeGame                                | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.NativeMobile                              | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.NetCrossPlat                              | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.NetWeb                                    | 17.9.34606.255  |
| Microsoft.VisualStudio.Workload.Node                                      | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.Office                                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.Python                                    | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.Universal                                 | 17.9.34511.75   |
| Microsoft.VisualStudio.Workload.VisualStudioExtension                     | 17.9.34511.75   |
| runtimes.ios                                                              | 8.0.224.6711    |
| runtimes.ios.net7                                                         | 8.0.224.6711    |
| runtimes.maccatalyst                                                      | 8.0.224.6711    |
| runtimes.maccatalyst.net7                                                 | 8.0.224.6711    |
| wasm.tools                                                                | 8.0.224.6711    |
| ProBITools.MicrosoftAnalysisServicesModelingProjects2022                  | 3.0.4           |
| ProBITools.MicrosoftReportProjectsforVisualStudio2022                     | 3.0.1           |
| SSIS.MicrosoftDataToolsIntegrationServices                                | 1.3.2           |
| VisualStudioClient.MicrosoftVisualStudio2022InstallerProjects             | 2.0.1           |
| Windows Driver Kit                                                        | 10.1.22621.2428 |
| Windows Driver Kit Visual Studio Extension                                | 10.0.22621.0    |
| Windows Software Development Kit                                          | 10.1.22621.2428 |
| WixToolset.WixToolsetVisualStudio2022Extension                            | 1.0.0.22        |

#### Microsoft Visual C++
| Name                                         | Architecture | Version     |
| -------------------------------------------- | ------------ | ----------- |
| Microsoft Visual C++ 2013 Additional Runtime | x64          | 12.0.40660  |
| Microsoft Visual C++ 2013 Minimum Runtime    | x64          | 12.0.40660  |
| Microsoft Visual C++ 2022 Additional Runtime | x64          | 14.38.33135 |
| Microsoft Visual C++ 2022 Debug Runtime      | x64          | 14.38.33135 |
| Microsoft Visual C++ 2022 Minimum Runtime    | x64          | 14.38.33135 |
| Microsoft Visual C++ 2022 Additional Runtime | x86          | 14.38.33135 |
| Microsoft Visual C++ 2022 Debug Runtime      | x86          | 14.38.33135 |
| Microsoft Visual C++ 2022 Minimum Runtime    | x86          | 14.38.33135 |

#### Installed Windows SDKs
- 10.0.17763.0
- 10.0.19041.0
- 10.0.20348.0
- 10.0.22000.0
- 10.0.22621.0

### .NET Core Tools
- .NET Core SDK: 6.0.127, 6.0.203, 6.0.321, 6.0.419, 7.0.116, 7.0.203, 7.0.313, 7.0.406, 8.0.200
- .NET Framework: 4.8, 4.8.1
- Microsoft.AspNetCore.App: 6.0.5, 6.0.26, 6.0.27, 7.0.5, 7.0.16, 8.0.2
- Microsoft.NETCore.App: 6.0.5, 6.0.26, 6.0.27, 7.0.5, 7.0.16, 8.0.2
- Microsoft.WindowsDesktop.App: 6.0.5, 6.0.26, 6.0.27, 7.0.5, 7.0.16, 8.0.2
- nbgv 3.6.133+2d32d93cb1

### PowerShell Tools
- PowerShell 7.4.1

#### Powershell Modules
- Az: 9.3.0
- Azure: 2.1.0 (Default), 5.3.0
- AzureRM: 2.1.0 (Default), 6.13.1
- Az (Cached): 7.5.0.zip
- Azure (Cached): 3.8.0.zip, 4.2.1.zip, 5.1.1.zip
- AzureRM (Cached): 3.8.0.zip, 4.2.1.zip, 5.1.1.zip, 6.7.0.zip
- AWSPowershell: 4.1.533
- DockerMsftProvider: 1.0.0.8
- MarkdownPS: 1.9
- Microsoft.Graph: 2.15.0
- Pester: 3.4.0, 5.5.0
- PowerShellGet: 1.0.0.1, 2.2.5
- PSScriptAnalyzer: 1.22.0
- PSWindowsUpdate: 2.2.1.4
- SqlServer: 22.2.0
- VSSetup: 2.2.16
```
Azure PowerShell module 2.1.0 and AzureRM PowerShell module 2.1.0 are installed
and are available via 'Get-Module -ListAvailable'.
All other versions are saved but not installed.
```

### Android
| Package Name               | Version                                                                                                                                                                                           |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Command Line Tools | 8.0                                                                                                                                                                                               |
| Android Emulator           | 31.2.9                                                                                                                                                                                            |
| Android SDK Build-tools    | 34.0.0<br>33.0.0 33.0.1 33.0.2 33.0.3<br>32.0.0<br>31.0.0                                                                                                                                         |
| Android SDK Platforms      | android-34-ext8 (rev 1)<br>android-34-ext10 (rev 1)<br>android-34 (rev 3)<br>android-33-ext5 (rev 1)<br>android-33-ext4 (rev 1)<br>android-33 (rev 3)<br>android-32 (rev 1)<br>android-31 (rev 1) |
| Android SDK Platform-Tools | 35.0.0                                                                                                                                                                                            |
| Android Support Repository | 47.0.0                                                                                                                                                                                            |
| CMake                      | 3.18.1<br>3.22.1                                                                                                                                                                                  |
| Google Play services       | 49                                                                                                                                                                                                |
| Google Repository          | 58                                                                                                                                                                                                |
| NDK                        | 24.0.8215888<br>25.2.9519653<br>26.2.11394342                                                                                                                                                     |

#### Environment variables
| Name                    | Value                                    |
| ----------------------- | ---------------------------------------- |
| ANDROID_HOME            | C:\Android\android-sdk                   |
| ANDROID_NDK             | C:\Android\android-sdk\ndk\25.2.9519653  |
| ANDROID_NDK_HOME        | C:\Android\android-sdk\ndk\25.2.9519653  |
| ANDROID_NDK_LATEST_HOME | C:\Android\android-sdk\ndk\26.2.11394342 |
| ANDROID_NDK_ROOT        | C:\Android\android-sdk\ndk\25.2.9519653  |
| ANDROID_SDK_ROOT        | C:\Android\android-sdk                   |

### Cached Docker images
| Repository:Tag                                                            | Digest                                                                   | Created    |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------- |
| mcr.microsoft.com/dotnet/framework/aspnet:4.8-windowsservercore-ltsc2022  | sha256:59926d7692cac2c349bd6f320d24bd9dbaeb7818a9c2c5f81b6d416b5a89789e  | 2024-02-13 |
| mcr.microsoft.com/dotnet/framework/runtime:4.8-windowsservercore-ltsc2022 | sha256:6e6e681d5bf0040611844b2b3f385afc0a44fbc06d258ab51979d04133f14c98  | 2024-02-13 |
| mcr.microsoft.com/dotnet/framework/sdk:4.8-windowsservercore-ltsc2022     | sha256:8ad2a6294e31cd60c794874e0a163b02664e09e7e62351083178fbe0c9ab122a  | 2024-02-13 |
| mcr.microsoft.com/windows/nanoserver:ltsc2022                             | sha256:64b22e42a69ebcdb86e49bf50780b64156431a508f7f06ac3050c71920fe57b7  | 2024-02-07 |
| mcr.microsoft.com/windows/servercore:ltsc2022                             | sha256:8a75266be74ad7a904470e18057f6fd62055cf7028172307fefc67aff37dfd10  | 2024-02-07 |

