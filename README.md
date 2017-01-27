# .Net Core

Full .NET Framework 4.6.1 support, this template has been tested on Windows 10, Debian 8 (Jessie) ans OSX 10. Works great with VSCode IDE!

## .NET Core
https://www.microsoft.com/net/core

### Debian

```bash
sudo apt-get install curl libunwind8 gettext
curl -sSL -o dotnet.tar.gz https://go.microsoft.com/fwlink/?LinkID=835021
sudo mkdir -p /opt/dotnet && sudo tar zxf dotnet.tar.gz -C /opt/dotnet
sudo ln -s /opt/dotnet/dotnet /usr/local/bin
```

## Frameworks
https://docs.microsoft.com/en-us/dotnet/articles/core/packages#frameworks

Currently this project has the following frameworks loaded

* Net461
* netcoreapp1.1

## Runtimes
https://docs.microsoft.com/en-us/dotnet/articles/core/rid-catalog

These are the runtimes loaded in this project

* win7-x64 
* win10-x64
* debian.8-x64
* osx.10.10-x64

## VScode
https://code.visualstudio.com

### .Net Core Project Manager (Nuget)

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter. 

`ext install net-core-project-manager`

## Mono 

If you want to compile for Windows and just run your binary on Debian you can install Mono.

`sudo apt-get install mono-complete`

http://www.mono-project.com/archived/running_your_first_mono_application/
