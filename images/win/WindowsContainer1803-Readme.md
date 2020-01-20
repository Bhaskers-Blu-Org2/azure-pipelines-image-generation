# Azure Pipelines Windows Container 1803 image

The following software is installed on machines in the Azure Pipelines **Windows Container 1803** (v20200116.1) pool.

Components marked with **\*** have been upgraded since the previous version of the image.


## Chocolatey

_Version:_ 0.10.15<br/>
_Environment:_
* PATH: contains location for choco.exe

## Docker

_Version:_ 19.03.5<br/>
_Environment:_
* PATH: contains location of docker.exe

## Docker-compose

_Version:_ 1.25.0<br/>
_Environment:_
* PATH: contains location of docker-compose.exe

## Powershell Core

_Version:_ 6.2.3<br/>

## Docker images

The following container images have been cached:
* microsoft/windowsservercore:1803 (Digest: sha256:04efd04d1e4761810dd11a0047b3e5736ace7783a3b3f8147a8b8835bdd00207)
* microsoft/nanoserver:1803 (Digest: sha256:0b4cfdfe41eba10094cf6c0645926bca8829fe37e820c3e7dbc682e2bda0e8a6)
* microsoft/aspnet:4.7.2-windowsservercore-1803 (Digest: sha256:a55aebebbbc4a56f6342e8f5e6eabc0ef0112de3c1b0cdae93739f7f894b0f5d)
* mcr.microsoft.com/windows/servercore:1803 (Digest: <none>)
* mcr.microsoft.com/windows/nanoserver:1803 (Digest: <none>)
* microsoft/dotnet-framework:4.7.2-sdk-windowsservercore-1803 (Digest: sha256:8d5052ef39a8caa4bebf2d99059cfd693351898cf08bb381a909ba00ef3fbe3b)
* microsoft/aspnetcore-build:2.0-nanoserver-1803 (Digest: sha256:82ad5218bb554d0b44ca54c21aba78b5ae10b92cead389d71328614b99fc47af)

## Node.js

_Version:_ 12.14.1<br/>
_Architecture:_ x64<br/>
_Environment:_
* PATH: contains location of node.exe<br/>
* Gulp CLI version: 2.2.0 Local version: Unknown<br/>
* Grunt grunt-cli v1.3.2<br/>
* Yarn 1.21.1<br/>

> Note: You can install and use another version of Node.js on Microsoft-hosted agent pools using the [Node tool installer](https://docs.microsoft.com/vsts/pipelines/tasks/tool/node-js) task.

## npm

_Version:_ 6.13.4<br/>
_Environment:_
* PATH: contains location of npm.cmd

## .NET Core

The following runtimes and SDKs are installed:

_Environment:_
* PATH: contains location of dotnet.exe

_SDK:_
* 3.1.101 C:\Program Files\dotnet\sdk\3.1.101
* 3.1.100 C:\Program Files\dotnet\sdk\3.1.100
* 3.0.102 C:\Program Files\dotnet\sdk\3.0.102
* 3.0.101 C:\Program Files\dotnet\sdk\3.0.101
* 3.0.100 C:\Program Files\dotnet\sdk\3.0.100
* 2.1.803 C:\Program Files\dotnet\sdk\2.1.803
* 2.1.802 C:\Program Files\dotnet\sdk\2.1.802
* 2.1.801 C:\Program Files\dotnet\sdk\2.1.801
* 2.1.701 C:\Program Files\dotnet\sdk\2.1.701
* 2.1.700 C:\Program Files\dotnet\sdk\2.1.700
* 2.1.608 C:\Program Files\dotnet\sdk\2.1.608
* 2.1.607 C:\Program Files\dotnet\sdk\2.1.607
* 2.1.606 C:\Program Files\dotnet\sdk\2.1.606
* 2.1.605 C:\Program Files\dotnet\sdk\2.1.605
* 2.1.604 C:\Program Files\dotnet\sdk\2.1.604
* 2.1.603 C:\Program Files\dotnet\sdk\2.1.603
* 2.1.602 C:\Program Files\dotnet\sdk\2.1.602
* 2.1.511 C:\Program Files\dotnet\sdk\2.1.511
* 2.1.510 C:\Program Files\dotnet\sdk\2.1.510
* 2.1.509 C:\Program Files\dotnet\sdk\2.1.509
* 2.1.508 C:\Program Files\dotnet\sdk\2.1.508
* 2.1.507 C:\Program Files\dotnet\sdk\2.1.507
* 2.1.506 C:\Program Files\dotnet\sdk\2.1.506
* 2.1.505 C:\Program Files\dotnet\sdk\2.1.505
* 2.1.504 C:\Program Files\dotnet\sdk\2.1.504
* 2.1.503 C:\Program Files\dotnet\sdk\2.1.503
* 2.1.502 C:\Program Files\dotnet\sdk\2.1.502
* 2.1.500 C:\Program Files\dotnet\sdk\2.1.500
* 2.1.403 C:\Program Files\dotnet\sdk\2.1.403
* 2.1.402 C:\Program Files\dotnet\sdk\2.1.402
* 2.1.401 C:\Program Files\dotnet\sdk\2.1.401
* 2.1.302 C:\Program Files\dotnet\sdk\2.1.302
* 2.1.301 C:\Program Files\dotnet\sdk\2.1.301
* 2.1.300 C:\Program Files\dotnet\sdk\2.1.300

_Runtime:_
* 3.1.1 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\3.1.1
* 3.1.0 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\3.1.0
* 3.0.2 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\3.0.2
* 3.0.1 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\3.0.1
* 3.0.0 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\3.0.0
* 2.1.9 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.9
* 2.1.8 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.8
* 2.1.7 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.7
* 2.1.6 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.6
* 2.1.5 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.5
* 2.1.4 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.4
* 2.1.3 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.3
* 2.1.2 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.2
* 2.1.15 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.15
* 2.1.14 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.14
* 2.1.13 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.13
* 2.1.12 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.12
* 2.1.11 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.11
* 2.1.10 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.10
* 2.1.1 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.1
* 2.1.0 C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.1.0

## Git

_Version:_ 2.25.0<br/>
_Environment:_
* PATH: contains location of git.exe

## Git Large File Storage (LFS)

_Version:_ 2.9.2<br/>
_Environment:_
* PATH: contains location of git-lfs.exe
* GIT_LFS_PATH: location of git-lfs.exe

## Subversion

_Version:_ 1.8.17<br/>
_Environment:_
* PATH: contains location of svn.exe
