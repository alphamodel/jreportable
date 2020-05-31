# jreportable

Download JRE from Release tab:

- 32 bit JRE: [jre-8u241-windows-i586.tar.gz for 32bit](https://github.com/alphamodel/jreportable/releases/download/v1.0/jre-8u241-windows-i586.tar.gz)
- 64 bit JRE: [jre-8u241-windows-x64.tar.gz for 64bit](https://github.com/alphamodel/jreportable/releases/download/v1.0/jre-8u241-windows-x64.tar.gz)

and run following command in the decompressed folder:

```batch
@for /R %%f in (*.pack) do ("bin\unpack200.exe" -rv "%%f" "%%~dpnf.jar" | find "Unpacking")
```
