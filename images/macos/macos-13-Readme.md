| Announcements |
|-|
| [[All OSes] Powershell Core will be updated to 7.4.x LTS on January, 28](https://github.com/actions/runner-images/issues/9115) |
***
# macOS 13
- OS Version: macOS 13.6.4 (22G513)
- Kernel Version: Darwin 22.6.0
- Image Version: 20240204.1

## Installed Software

### Language and Runtime
- .NET Core SDK: 7.0.102, 7.0.202, 7.0.306, 7.0.405, 8.0.101
- Bash 3.2.57(1)-release
- Clang/LLVM 15.0.0
- Clang/LLVM (Homebrew) 15.0.7 - available on `$(brew --prefix llvm@15)/bin/clang`
- GCC 11 (Homebrew GCC 11.4.0) - available by `gcc-11` alias
- GCC 12 (Homebrew GCC 12.3.0) - available by `gcc-12` alias
- GCC 13 (Homebrew GCC 13.2.0) - available by `gcc-13` alias
- GNU Fortran 11 (Homebrew GCC 11.4.0) - available by `gfortran-11` alias
- GNU Fortran 12 (Homebrew GCC 12.3.0) - available by `gfortran-12` alias
- GNU Fortran 13 (Homebrew GCC 13.2.0) - available by `gfortran-13` alias
- Kotlin 1.9.22-release-704
- Mono 6.12.0.188
- Node.js 20.11.0
- Perl 5.38.2
- PHP 8.3.2
- Python3 3.12.1
- Ruby 3.0.6p216

### Package Management
- Bundler 2.5.5
- Carthage 0.39.1
- CocoaPods 1.15.0
- Composer 2.6.6
- Homebrew 4.2.6
- NPM 10.2.4
- NuGet 6.3.1.1
- Pip3 24.0 (python 3.12)
- Pipx 1.4.3
- RubyGems 3.5.5
- Vcpkg 2024 (build from commit 80403036a)
- Yarn 1.22.19

### Project Management
- Apache Ant 1.10.14
- Apache Maven 3.9.6
- Gradle 8.6

### Utilities
- 7-Zip 17.05
- aria2 1.37.0
- azcopy 10.23.0
- bazel 7.0.2
- bazelisk 1.19.0
- bsdtar 3.5.3 - available by 'tar' alias
- Curl 8.6.0
- Git 2.43.0
- Git LFS 3.4.1
- GitHub CLI 2.43.1
- GNU Tar 1.35 - available by 'gtar' alias
- GNU Wget 1.21.4
- gpg (GnuPG) 2.4.4
- jq 1.7.1
- OpenSSL 1.1.1w  11 Sep 2023
- Packer 1.9.4
- pkg-config 0.29.2
- yq 4.40.5
- zstd 1.5.5

### Tools
- AWS CLI 2.15.17
- AWS SAM CLI 1.108.0
- AWS Session Manager CLI 1.2.553.0
- Azure CLI 2.56.0
- Azure CLI (azure-devops) 0.26.0
- Bicep CLI 0.24.24
- Cmake 3.28.2
- CodeQL Action Bundle 2.16.1
- Fastlane 2.219.0
- SwiftFormat 0.53.1
- Xcbeautify 1.4.0
- Xcode Command Line Tools 15.1.0.0.1.1700200546
- Xcodes 1.4.1

### Linters
- SwiftLint 0.53.0

### Browsers
- Safari 17.3 (18617.2.4.11.11)
- SafariDriver 17.3 (18617.2.4.11.11)
- Google Chrome 121.0.6167.139
- Google Chrome for Testing 121.0.6167.85
- ChromeDriver 121.0.6167.85
- Microsoft Edge 121.0.2277.98
- Microsoft Edge WebDriver 121.0.2277.98
- Mozilla Firefox 122.0
- geckodriver 0.34.0
- Selenium server 4.17.0

#### Environment variables
| Name            | Value                                 |
| --------------- | ------------------------------------- |
| CHROMEWEBDRIVER | /usr/local/share/chromedriver-mac-x64 |
| EDGEWEBDRIVER   | /usr/local/share/edge_driver          |
| GECKOWEBDRIVER  | /usr/local/opt/geckodriver/bin        |

### Java
| Version             | Environment Variable |
| ------------------- | -------------------- |
| 8.0.402+6           | JAVA_HOME_8_X64      |
| 11.0.22+7           | JAVA_HOME_11_X64     |
| 17.0.10+7 (default) | JAVA_HOME_17_X64     |
| 21.0.2+13.0         | JAVA_HOME_21_X64     |

### Cached Tools

#### Ruby
- 3.0.6
- 3.1.4

#### PyPy
- 2.7.18 [PyPy 7.3.15]
- 3.7.13 [PyPy 7.3.9]
- 3.8.16 [PyPy 7.3.11]
- 3.9.18 [PyPy 7.3.15]
- 3.10.13 [PyPy 7.3.15]

#### Python
- 3.8.18
- 3.9.18
- 3.10.13
- 3.11.7
- 3.12.1

#### Node.js
- 16.20.2
- 18.19.0
- 20.11.0

#### Go
- 1.19.13
- 1.20.13
- 1.21.6

### Rust Tools
- Cargo 1.75.0
- Rust 1.75.0
- Rustdoc 1.75.0
- Rustup 1.26.0

#### Packages
- Clippy 0.1.75
- Rustfmt 1.7.0-stable

### PowerShell Tools
- PowerShell 7.4.1

#### PowerShell Modules
- Az: 11.2.0
- Pester: 5.5.0
- PSScriptAnalyzer: 1.21.0

### Xcode
| Version          | Build   | Path                           |
| ---------------- | ------- | ------------------------------ |
| 15.2             | 15C500b | /Applications/Xcode_15.2.app   |
| 15.1             | 15C65   | /Applications/Xcode_15.1.app   |
| 15.0.1 (default) | 15A507  | /Applications/Xcode_15.0.1.app |
| 14.3.1           | 14E300c | /Applications/Xcode_14.3.1.app |
| 14.2             | 14C18   | /Applications/Xcode_14.2.app   |
| 14.1             | 14B47b  | /Applications/Xcode_14.1.app   |

#### Installed SDKs
| SDK                                                     | SDK Name                                      | Xcode Version |
| ------------------------------------------------------- | --------------------------------------------- | ------------- |
| macOS 13.0                                              | macosx13.0                                    | 14.1          |
| macOS 13.1                                              | macosx13.1                                    | 14.2          |
| macOS 13.3                                              | macosx13.3                                    | 14.3.1        |
| macOS 14.0                                              | macosx14.0                                    | 15.0.1        |
| macOS 14.2                                              | macosx14.2                                    | 15.1, 15.2    |
| iOS 16.1                                                | iphoneos16.1                                  | 14.1          |
| iOS 16.2                                                | iphoneos16.2                                  | 14.2          |
| iOS 16.4                                                | iphoneos16.4                                  | 14.3.1        |
| iOS 17.0                                                | iphoneos17.0                                  | 15.0.1        |
| iOS 17.2                                                | iphoneos17.2                                  | 15.1, 15.2    |
| Simulator - iOS 16.1                                    | iphonesimulator16.1                           | 14.1          |
| Simulator - iOS 16.2                                    | iphonesimulator16.2                           | 14.2          |
| Simulator - iOS 16.4                                    | iphonesimulator16.4                           | 14.3.1        |
| Simulator - iOS 17.0                                    | iphonesimulator17.0                           | 15.0.1        |
| Simulator - iOS 17.2                                    | iphonesimulator17.2                           | 15.1, 15.2    |
| tvOS 16.1                                               | appletvos16.1                                 | 14.1, 14.2    |
| tvOS 16.4                                               | appletvos16.4                                 | 14.3.1        |
| tvOS 17.0                                               | appletvos17.0                                 | 15.0.1        |
| tvOS 17.2                                               | appletvos17.2                                 | 15.1, 15.2    |
| Simulator - tvOS 16.1                                   | appletvsimulator16.1                          | 14.1, 14.2    |
| Simulator - tvOS 16.4                                   | appletvsimulator16.4                          | 14.3.1        |
| Simulator - tvOS 17.0                                   | appletvsimulator17.0                          | 15.0.1        |
| Simulator - tvOS 17.2                                   | appletvsimulator17.2                          | 15.1, 15.2    |
| watchOS 9.1                                             | watchos9.1                                    | 14.1, 14.2    |
| watchOS 9.4                                             | watchos9.4                                    | 14.3.1        |
| watchOS 10.0                                            | watchos10.0                                   | 15.0.1        |
| watchOS 10.2                                            | watchos10.2                                   | 15.1, 15.2    |
| Simulator - watchOS 9.1                                 | watchsimulator9.1                             | 14.1, 14.2    |
| Simulator - watchOS 9.4                                 | watchsimulator9.4                             | 14.3.1        |
| Simulator - watchOS 10.0                                | watchsimulator10.0                            | 15.0.1        |
| Simulator - watchOS 10.2                                | watchsimulator10.2                            | 15.1, 15.2    |
| Simulator - visionOS 1.0                                | xrsimulator1.0                                | 15.2          |
| visionOS 1.0                                            | xros1.0                                       | 15.2          |
| Asset Runtime SDK for macOS hosts targeting watchOS 9.4 | assetruntime.host.macosx.target.watchos9.4    | 14.3.1        |
| Asset Runtime SDK for macOS hosts targeting iOS 16.4    | assetruntime.host.macosx.target.iphoneos16.4  | 14.3.1        |
| Asset Runtime SDK for macOS hosts targeting tvOS 16.4   | assetruntime.host.macosx.target.appletvos16.4 | 14.3.1        |
| DriverKit 22.1                                          | driverkit22.1                                 | 14.1          |
| DriverKit 22.2                                          | driverkit22.2                                 | 14.2          |
| DriverKit 22.4                                          | driverkit22.4                                 | 14.3.1        |
| DriverKit 23.0                                          | driverkit23.0                                 | 15.0.1        |
| DriverKit 23.2                                          | driverkit23.2                                 | 15.1, 15.2    |

#### Installed Simulators
| OS           | Xcode Version                                    | Simulators                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------ | ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| iOS 16.1     | 14.1                                             | iPhone 14<br>iPhone 14 Plus<br>iPhone 14 Pro<br>iPhone 14 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air (5th generation)<br>iPad mini (6th generation)<br>iPad Pro (11-inch) (4th generation)<br>iPad Pro (12.9-inch) (6th generation)                                                                                                                                                                                             |
| iOS 16.2     | 14.2                                             | iPhone 14<br>iPhone 14 Plus<br>iPhone 14 Pro<br>iPhone 14 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air (5th generation)<br>iPad mini (6th generation)<br>iPad Pro (11-inch) (4th generation)<br>iPad Pro (12.9-inch) (6th generation)                                                                                                                                                                                             |
| iOS 16.4     | 14.3.1                                           | iPhone 14<br>iPhone 14 Plus<br>iPhone 14 Pro<br>iPhone 14 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air (5th generation)<br>iPad mini (6th generation)<br>iPad Pro (11-inch) (4th generation)<br>iPad Pro (12.9-inch) (6th generation)                                                                                                                                                                                             |
| iOS 17.0     | 14.1<br>14.2<br>14.3.1<br>15.0.1<br>15.1<br>15.2 | iPhone 14<br>iPhone 14 Plus<br>iPhone 14 Pro<br>iPhone 14 Pro Max<br>iPhone 15<br>iPhone 15 Plus<br>iPhone 15 Pro<br>iPhone 15 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air (5th generation)<br>iPad mini (6th generation)<br>iPad Pro (11-inch) (4th generation)<br>iPad Pro (12.9-inch) (6th generation)                                                                                                                        |
| iOS 17.2     | 14.1<br>14.2<br>14.3.1<br>15.0.1<br>15.1<br>15.2 | iPhone 14<br>iPhone 14 Plus<br>iPhone 14 Pro<br>iPhone 14 Pro Max<br>iPhone 15<br>iPhone 15 Plus<br>iPhone 15 Pro<br>iPhone 15 Pro Max<br>iPhone SE (3rd generation)<br>iPad (10th generation)<br>iPad Air (5th generation)<br>iPad mini (6th generation)<br>iPad Pro (11-inch) (4th generation)<br>iPad Pro (12.9-inch) (6th generation)                                                                                                                        |
| tvOS 16.1    | 14.1<br>14.2<br>14.3.1<br>15.0.1<br>15.1<br>15.2 | Apple TV<br>Apple TV 4K (3rd generation)<br>Apple TV 4K (3rd generation) (at 1080p)                                                                                                                                                                                                                                                                                                                                                                              |
| tvOS 16.4    | 14.1<br>14.2<br>14.3.1<br>15.0.1<br>15.1<br>15.2 | Apple TV<br>Apple TV 4K (3rd generation)<br>Apple TV 4K (3rd generation) (at 1080p)                                                                                                                                                                                                                                                                                                                                                                              |
| tvOS 17.0    | 14.1<br>14.2<br>14.3.1<br>15.0.1<br>15.1<br>15.2 | Apple TV<br>Apple TV 4K (3rd generation)<br>Apple TV 4K (3rd generation) (at 1080p)                                                                                                                                                                                                                                                                                                                                                                              |
| tvOS 17.2    | 14.1<br>14.2<br>14.3.1<br>15.0.1<br>15.1<br>15.2 | Apple TV<br>Apple TV 4K (3rd generation)<br>Apple TV 4K (3rd generation) (at 1080p)                                                                                                                                                                                                                                                                                                                                                                              |
| watchOS 9.1  | 14.1<br>14.2<br>14.3.1<br>15.0.1<br>15.1<br>15.2 | Apple Watch SE (40mm) (2nd generation)<br>Apple Watch SE (44mm) (2nd generation)<br>Apple Watch Series 5 (40mm)<br>Apple Watch Series 5 (44mm)<br>Apple Watch Series 6 (40mm)<br>Apple Watch Series 6 (44mm)<br>Apple Watch Series 7 (41mm)<br>Apple Watch Series 7 (45mm)<br>Apple Watch Series 8 (41mm)<br>Apple Watch Series 8 (45mm)<br>Apple Watch Ultra (49mm)                                                                                             |
| watchOS 9.4  | 14.1<br>14.2<br>14.3.1<br>15.0.1<br>15.1<br>15.2 | Apple Watch SE (40mm) (2nd generation)<br>Apple Watch SE (44mm) (2nd generation)<br>Apple Watch Series 5 (40mm)<br>Apple Watch Series 5 (44mm)<br>Apple Watch Series 6 (40mm)<br>Apple Watch Series 6 (44mm)<br>Apple Watch Series 7 (41mm)<br>Apple Watch Series 7 (45mm)<br>Apple Watch Series 8 (41mm)<br>Apple Watch Series 8 (45mm)<br>Apple Watch Ultra (49mm)                                                                                             |
| watchOS 10.0 | 14.1<br>14.2<br>14.3.1<br>15.0.1<br>15.1<br>15.2 | Apple Watch SE (40mm) (2nd generation)<br>Apple Watch SE (44mm) (2nd generation)<br>Apple Watch Series 5 (40mm)<br>Apple Watch Series 5 (44mm)<br>Apple Watch Series 6 (40mm)<br>Apple Watch Series 6 (44mm)<br>Apple Watch Series 7 (41mm)<br>Apple Watch Series 7 (45mm)<br>Apple Watch Series 8 (41mm)<br>Apple Watch Series 8 (45mm)<br>Apple Watch Series 9 (41mm)<br>Apple Watch Series 9 (45mm)<br>Apple Watch Ultra (49mm)<br>Apple Watch Ultra 2 (49mm) |
| watchOS 10.2 | 14.1<br>14.2<br>14.3.1<br>15.0.1<br>15.1<br>15.2 | Apple Watch SE (40mm) (2nd generation)<br>Apple Watch SE (44mm) (2nd generation)<br>Apple Watch Series 5 (40mm)<br>Apple Watch Series 5 (44mm)<br>Apple Watch Series 6 (40mm)<br>Apple Watch Series 6 (44mm)<br>Apple Watch Series 7 (41mm)<br>Apple Watch Series 7 (45mm)<br>Apple Watch Series 8 (41mm)<br>Apple Watch Series 8 (45mm)<br>Apple Watch Series 9 (41mm)<br>Apple Watch Series 9 (45mm)<br>Apple Watch Ultra (49mm)<br>Apple Watch Ultra 2 (49mm) |

### Android
| Package Name               | Version                                                                                                                                               |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Command Line Tools | 11.0                                                                                                                                                  |
| Android Emulator           | 33.1.24                                                                                                                                               |
| Android SDK Build-tools    | 34.0.0<br>33.0.2 33.0.3                                                                                                                               |
| Android SDK Platforms      | android-34-ext8 (rev 1)<br>android-34-ext10 (rev 1)<br>android-34 (rev 2)<br>android-33-ext5 (rev 1)<br>android-33-ext4 (rev 1)<br>android-33 (rev 3) |
| Android SDK Platform-Tools | 34.0.5                                                                                                                                                |
| Android Support Repository | 47.0.0                                                                                                                                                |
| CMake                      | 3.22.1                                                                                                                                                |
| Google Play services       | 49                                                                                                                                                    |
| Google Repository          | 58                                                                                                                                                    |
| NDK                        | 24.0.8215888<br>25.2.9519653<br>26.1.10909125 (default)                                                                                               |

#### Environment variables
| Name                    | Value                                               |
| ----------------------- | --------------------------------------------------- |
| ANDROID_HOME            | /Users/runner/Library/Android/sdk                   |
| ANDROID_NDK             | /Users/runner/Library/Android/sdk/ndk/26.1.10909125 |
| ANDROID_NDK_HOME        | /Users/runner/Library/Android/sdk/ndk/26.1.10909125 |
| ANDROID_NDK_LATEST_HOME | /Users/runner/Library/Android/sdk/ndk/26.1.10909125 |
| ANDROID_NDK_ROOT        | /Users/runner/Library/Android/sdk/ndk/26.1.10909125 |
| ANDROID_SDK_ROOT        | /Users/runner/Library/Android/sdk                   |

