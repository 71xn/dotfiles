# 🧪 Finn Lestrange's dotfiles

> This is my collection of dotfiles for my Windows 10 development machines.

## Instalation Steps

### Prerequisite Steps

* Install [winget package manager](ms-appinstaller:?source=https://aka.ms/getwinget), if that doesn't work, go to [winget.run](https://winget.run/).
* `winget import winget-packages.json`

### Main Install Steps

1. Install `Windows Terminal` & `oh-my-posh` - *if not following prerequisite steps, else skip to step 2*
    * `winget install JanDeDobbeleer.OhMyPosh; winget install -e --id Microsoft.WindowsTerminal`
2. Copy `material.omp.json` to ` ~\AppData\Local\Programs\oh-my-posh\themes\`
3. Copy `prompt.ps1` to `~\Documents\WindowsPowerShell`
4. Overwrite your Windows Terminal settings with `settings.json`