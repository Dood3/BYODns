- Just a quick dns server in C# with custom TXT entries to use for intentional bad things that are actually good..
```
dotnet publish -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true -p:PublishReadyToRun=true -p:PublishTrimmed=true -p:IncludeNativeLibrariesForSelfExtract=true -p:PublishDir=.\publish --force
```
