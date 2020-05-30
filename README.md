# jreportable

Download JRE from Release tab, and run following command in the decompressed folder.

```batch
@for /R %%f in (*.pack) do ("bin\unpack200.exe" -rv "%%f" "%%~dpnf.jar" | find "Unpacking")
```
