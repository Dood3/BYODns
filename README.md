-- Build an executable from the Developer Console within Visual studio

https://learn.microsoft.com/en-us/dotnet/core/deploying/single-file/overview?tabs=cli
```
dotnet publish -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true -p:PublishReadyToRun=true -p:PublishTrimmed=true -p:IncludeNativeLibrariesForSelfExtract=true -p:PublishDir=.\publish --force
```
