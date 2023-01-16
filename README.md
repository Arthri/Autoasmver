---

# DEPRECATED

Moved to [Arthri/Belp](https://github.com/Arthri/Belp)

---

# Autoasmver
[![Project License](https://img.shields.io/badge/license-MIT%20OR%20MIT--0%20OR%20Apache--2.0-green?style=flat-square "License")](https://github.com/Arthri/Autoasmver#License) [![NuGet](https://img.shields.io/nuget/v/Autoasmver?style=flat-square "Latest NuGet Release")](https://www.nuget.org/packages/Autoasmver/latest)

Autoasmver automatically sets the assembly version to the last major version. For example,
- If the NuGet version is `1.4.2`, the assembly version is `1.0.0.0`
- If the NuGet version is `2.6.9`, the assembly version is `2.0.0.0`
- If the NuGet version is `3.0.9`, the assembly version is `3.0.0.0`
- If the NuGet version is `4.0.0`, the assembly version is `4.0.0.0`

## Why?
https://codingforsmarties.wordpress.com/2016/01/21/how-to-version-assemblies-destined-for-nuget/

## Installation

### Requirements
- SDK-style project / .NET Core+ project / .NET 5+ project

### Install using Visual Studio Package Manager
1. Open Visual Studio
1. Right click the project in the Solution Explorer
1. Click on "Manage NuGet Packages"
1. Go to the "Browse" tab
1. Search for `Autoasmver`
1. Install

### Install using .NET CLI
1. Open a terminal
1. Navigate to the project's `.csproj`
1. Run `dotnet add package Autoasmver`

## Usage
No input required

## License
This work is available under different licenses: [`MIT`][MIT], [`MIT-0`][MIT-0], and [`Apache 2.0`][Apache_2.0]

[MIT]: https://github.com/Arthri/Autoasmver/blob/6eeacae258e66e307ee0b8ca2d27b2e6d7a8a63e/LICENSE-MIT
[MIT-0]: https://github.com/Arthri/Autoasmver/blob/6eeacae258e66e307ee0b8ca2d27b2e6d7a8a63e/LICENSE
[Apache_2.0]: https://github.com/Arthri/Autoasmver/blob/6eeacae258e66e307ee0b8ca2d27b2e6d7a8a63e/LICENSE-Apache_2.0
