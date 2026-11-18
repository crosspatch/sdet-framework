This is a test repo for practice.

Prereqs: SDK version 10.0.4xx(enforced with global.json)

Setup
1. ```git clone``` https://github.com/crosspatch/sdet-framework.git
1. Navigate to the folder with the slnx file - ```cd sdet-framework```.
1. ```dotnet build``` (This generates the ps1 file)
1. ```pwsh SdetFramework.Tests/bin/Debug/net10.0/playwright.ps1 install```
1. ```dotnet test```