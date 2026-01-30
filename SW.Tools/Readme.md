

Creamos el paquete nuget con el siguiente comando:
```powershell
nuget pack .\SW.Tools\SW.Tools.csproj -Prop Configuration=Release
```

```bash
dotnet nuget push SW.Tools.1.0.12.3.nupkg --source "github" --configfile .\SW.Tools\nuget.config
```