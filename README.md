# setup-win

> I'm currently workiing on a re-write of these docs

Set up a fresh Windows 10/11 install the easy way using the Chocolatey package manager.

Fork and change it to your favourite apps. Mine will be a fairly minimal gaming rig.

> 💡 I also have guides for [macOS](https://github.com/miclgael/setup) and [Linux](https://github.com/miclgael/setup-linux)!

## 🍫 Install [Chocolatey](https://chocolatey.org/install) Package Manager

1. Open **Windows Powershell** as Administrator
2. Install Chocolatey with the command: 
```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
3. Close and reopen Powershell, or open CMD as Admin, instead.
4. Check it worked with `choco`

**Keep things updated:**

- Keep everything up to date with `choco upgrade all`
- Lock certain apps to a version with `choco upgrade all --except="'speccy,vlc'"` 

**List all installed packages + versions:**

```bash
choco version all
```

# TL;DR - All in one

```bash
choco install -y microsoft-windows-terminal firefox origin steam uplay goggalaxy vortex epicgameslauncher discord slack notion obs obs-studio virtualbox itunes icloud vlc 7zip ccleaner FiraCode-ttf powertoys dashlane authy-desktop
```

# Step-by-step

## 👩‍💻 Install [Windows Terminal](https://github.com/Microsoft/Terminal)

```bash
choco install -y microsoft-windows-terminal 
```

## 🔐 Install Password manager

```bash
choco install -y 1password
```

## 🦊 Install [Firefox](https://www.mozilla.org/en-US/firefox/new/)

```bash
choco install -y firefox
````

## 🎮 Install game launchers

```bash
choco install -y origin steam uplay goggalaxy vortex epicgameslauncher
```

## 🦜 Install chat clients

```bash
choco install -y discord slack
```

## Install other misc. bits

```bash
choco install -y obs obs-studio virtualbox itunes icloud vlc 7zip ccleaner 
```

## 📺 Install graphics drivers (Choose one)

- Team Green: [NVIDIA Experience](https://www.nvidia.com/Download/index.aspx)
- Team Red: [AMD Adrenaline](https://www.amd.com/en/support)

## 🎼 Install Sound drivers (Optional)

- [Komplete Audio 6](https://www.native-instruments.com/en/support/downloads/drivers-other-files/#kompleteaudio6)

## 🐧 Install some dev stuff (Optional)

- Install Windows Subsystem for Linux, enable it, enable Ubuntu (or your favourite flavour) (check Windows App Store)

## Extra stuff (Optional)

- [Xbox (Beta) app](https://www.microsoft.com/en-au/p/xbox-beta/9mv0b5hzvk9z)
- [Xbox Accessories app](https://www.microsoft.com/en-au/p/xbox-accessories/9nblggh30xj3)
- Install Fira-Code font: `choco install -y FiraCode-ttf`
- Install Windows PowerToys (Preview): `choco install -y powertoys`
- [Razer Synapse 3](https://www.razer.com/synapse-3)
- [Da Vinci Resolve 17 (Sign-up required)](https://www.blackmagicdesign.com/products/davinciresolve/#global-footer)
- Change Disk Letters (eg, **C:\\**, **E:\\**=WD Green, **G:\\**=Games, **R:\\**=WD Red (RAIDED), **V:\\**=VirtualMachines)
- DS4 Windows (a must have for PS controller users!)
- [Steam ROM Manager](https://steamgriddb.github.io/steam-rom-manager/)
- https://answers.microsoft.com/en-us/windows/forum/all/restore-old-right-click-context-menu-in-windows-11/a62e797c-eaf3-411b-aeec-e460e6e5a82a

## Web apps

- [Steam Grid DB](https://www.steamgriddb.com) - add custom banners and logos for your non-steam games.
