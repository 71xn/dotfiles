# 🧪 Finn Lestrange's dotfiles

> This is my collection of dotfiles for my Windows 10 development machines.

## Instalation Steps

### Prerequisite Steps

- Install [winget package manager](ms-appinstaller:?source=https://aka.ms/getwinget), if that doesn't work, go to [winget.run](https://winget.run/).
- `winget import winget-packages.json`

> You will also need a compatible font, I use and recommend JetBrains Mono Nerd Font, however, any Nerd Font should do fine. You can download [JetBrains Mono Here](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/JetBrainsMono.zip) or other Nerd Fonts [here](https://www.nerdfonts.com/).

### Main Install Steps

1. Install `Windows Terminal` & `oh-my-posh` - _if not following prerequisite steps, else skip to step 2_
   - `winget install JanDeDobbeleer.OhMyPosh; winget install -e --id Microsoft.WindowsTerminal`
2. Copy `material.omp.json` to ` ~\AppData\Local\Programs\oh-my-posh\themes\`
3. Copy `prompt.ps1` to `~\Documents\WindowsPowerShell`
4. Overwrite your Windows Terminal settings with `settings.json`
   - _First ensure that you have the `fonts`, `oh-my-posh`, and `git` installed. This will all be installed if you use the import script listed above._

## Setting Up VSCode

> Here is some basic information about my VSCode Setup, although I prefer to use a full IDE most of the time, Intellij Pro for Java, WebStorm for JS and PyCharm Pro for Python, it can be easier to use VSCode for editing markdown, configuration files, or simple JS projects.

- **Theme**: GitHub Dark Dimmed
- **Font**: JetBrains Mono Nerd Font (enables ligature support)

For a list of extensions I use, see: `extensions.list`

To install the same extensions as I have, run the `install-vscode-extensions.ps1` script in a powershell window.
