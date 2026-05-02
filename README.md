# LiteBar
A lightweight Windows tray utility for quick cleanup, Explorer recovery, power mode switching, shortcuts, and compact workflow controls.

It is designed to stay out of the way, run from the system tray, and give fast access to common Windows actions without opening heavy tools.

## Features

- Tray-first Windows utility
- Clean temporary files safely
- Restart Windows Explorer
- Switch power modes
- Global shortcuts
- Dark / Light / Follow System theme
- Arabic / English support
- Icon-only compact bar mode
- Startup with Windows option
- Portable EXE and MSI installer builds

## Downloads

Go to the latest release and download:

- `LiteBar.exe` — portable version
- `LiteBar-Setup.msi` — installer version

## Build

```powershell
dotnet publish "src\LiteBar\LiteBar.csproj" -c Release -r win-x64 --self-contained true /p:PublishSingleFile=true /p:IncludeNativeLibrariesForSelfExtract=true
