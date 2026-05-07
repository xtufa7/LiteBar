# LiteBar

<div align="center">

<h2>⚡ Lightweight Control Bar for Windows</h2>

<p>
LiteBar is a lightweight Windows tray utility for quick cleanup, Explorer recovery,
power mode switching, shortcuts, and compact workflow controls.
</p>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=18&pause=1000&color=2D5BFF&center=true&vCenter=true&width=650&lines=Clean+temporary+files+quickly...;Restart+Windows+Explorer+instantly...;Switch+power+modes+with+one+click...;Stay+lightweight+and+out+of+the+way..." />

<p>
Built to stay quiet in the system tray, open fast when needed,
and give quick access to useful Windows actions without heavy tools.
</p>

</div>

---

## ✨ Features

* Tray-first Windows utility
* Safe temporary files cleanup
* Restart Windows Explorer
* Switch power modes
* Global shortcuts
* Dark / Light / Follow System theme
* Arabic / English support
* Icon-only compact bar mode
* Startup with Windows option
* Portable EXE and MSI installer builds

---

## 🚧 Development Status

<div align="center">

<h3>More Improvements Are Coming</h3>

<p>
LiteBar is currently being improved with better performance,
cleaner behavior, smoother startup, and more reliable workflow controls.
</p>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=17&pause=1000&color=2D5BFF&center=true&vCenter=true&width=620&lines=Optimizing+startup+behavior...;Improving+tray+stability...;Refining+cleanup+logic...;More+polish+coming+soon..." />

<p>
The goal is simple: keep LiteBar fast, compact, and useful without getting in your way.
</p>

</div>

---

## 📦 Downloads

Go to the latest release and download:

* `LiteBar.exe` — portable version
* `LiteBar-Setup.msi` — installer version

---

## 🛠️ Build

```powershell
dotnet publish "src\LiteBar\LiteBar.csproj" -c Release -r win-x64 --self-contained true /p:PublishSingleFile=true /p:IncludeNativeLibrariesForSelfExtract=true
```
