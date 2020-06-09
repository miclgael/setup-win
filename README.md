# setup-win
Set up a fresh Windows 10 install the easy way using Chocolatey (the package manager... It's like a nerdier Ninite?)

Fork and change it to your favourite apps. Mine will be a fairly minimal gaming rig.

## 🍫 Install [Chocolatey](https://chocolatey.org/install)

1. Open **Windows Powershell** as Administrator
2. Install Chocolatey with the command: `Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))`
3. Close and reopen Powershell, or open CMD as Admin, instead.
4. Check it worked with `choco`

**Keep things updated:**

- Keep everything up to date with `choco upgrade all`
- Lock certain apps to a version with `choco upgrade all --except="'speccy,vlc'"` 

**List all installed packages + versions:**

```bash
choco version all
```

## 👩‍💻 Install Windows Terminal

```bash
choco install -y microsoft-windows-terminal 
```

## 🛡 Install Dashlane and Authy

```bash
choco install -y dashlane authy-desktop
```

## 🦊 Install Firefox and other Utils

```bash
choco install -y vlc 7zip ccleaner firefox
````

## 🎮 Install Game launchers and Chat clients

```bash
choco install -y discord origin steam uplay goggalaxy vortex epicgameslauncher
```

## Install graphics drivers

**Team Green:** [NVIDIA Experience](https://www.nvidia.com/Download/index.aspx)

---OR---

**Team Red:** [AMD Adrenaline](https://www.amd.com/en/support)

## Install some dev stuff

- Install Windows Subsystem for Linux, enable it, enable Ubuntu (or your favourite flavour) (check Windows App Store)

## Extra stuff

- [Xbox (Beta) app](https://www.microsoft.com/en-au/p/xbox-beta/9mv0b5hzvk9z)
- [Xbox Accessories app](https://www.microsoft.com/en-au/p/xbox-accessories/9nblggh30xj3)

## Settings to tweak

- **Set the background ([to this](https://uhdwallpapers.org/wallpaper/fallout-76_79856/2560x1440/) obviously):** Right-Click on Desktop > Personalise > Background 
- 

## Web apps

- [Steam Grid DB](https://www.steamgriddb.com) - add custom banners and logos for your non-steam games.

Note to self :)

```
7zip
dashlane 
discord
epicgameslauncher
firefox
FiraCode-ttf
goggalaxy
notion
obs
obs-studio
powertoys
slack
spotify
steam
uplay
virtualbox
vlc
vortex
```


https://www.razer.com/synapse-3
