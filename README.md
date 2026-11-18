This is a test repo for practice.

Prereqs: SDK version 10.0.4xx(enforced with global.json)

Once this repo is cloned, follow these steps to get set up.

1. Navigate to the folder with the slnx file(sdet-framework).
1. dotnet build(This generates the ps1 file)
1. pwsh <folder where ps1 file is> install(SdetFramework.Tests/bin/Debug/net10.0/playwright.ps1)
1. dotnet test