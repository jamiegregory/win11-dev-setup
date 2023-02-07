# Developer Setup for Microsoft Windows 11

Script to setup a development environment in Microsoft Windows 11.

## Usage

Open any Windows PowerShell host console **(Except Windows Terminal)** with administrator rights and run:

```Powershell
$GitHubRepositoryAuthor = "JamieGregory"; `
$GitHubRepositoryName = "win11-dev-setup"; `
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass; `
Invoke-Expression (Invoke-RestMethod -Uri "https://raw.githubusercontent.com/${GitHubRepositoryAuthor}/${GitHubRepositoryName}/main/Download.ps1");
```

## What does?

This dotfiles script does:

- Install Chocolatey.
- Configure Chocolatey to remember installation arguments for future updates.
- Install Hack Nerd Font.
- Install Git.
- Configure Git.
- Install Vim.
- Install Vim-Plug.
- Install Vim plugins.
- Install Visual Studio Code.
- Configure Visual Studio Code.
- Install Visual Studio Code extensions.
- Install Oh My Posh for PowerShell.
- Configure Oh My Posh theme.
- Install Posh-Git for Oh My Posh.
- Install Terminal-Icons for PowerShell.
- Configure PSWebSearch for PowerShell.
- Configure PSReadLine for PowerShell.
- Configure Windows Terminal.
- Install Notepad++.
- Configure Notepad++.
- Install .NET SDK.
- Enable Windows Subsystem for Linux.
- Install Ubuntu 20.04 LTS in WSL.
  - Install curl.
  - Install Neofetch.
  - Configure Git in Ubuntu.
  - Install Visual Studio Code extensions in Ubuntu.
  - Install Volta in Ubuntu.
    - Install Node.js LTS using Volta in Ubuntu.
    - Install NPM using Volta in Ubuntu.
    - Install Yarn using Volta in Ubuntu.
    - Install TypeScript using Volta in Ubuntu.
    - Install Yarn-Upgrade-All using Volta in Ubuntu.
    - Install NestJS CLI using Volta in Ubuntu.
  - Install Golang in Ubuntu.
  - Install HUGO in Ubuntu.
  - Install Vim in Ubuntu.
  - Install Vim-Plug in Ubuntu.
  - Install Vim plugins in Ubuntu.
  - Install Zsh in Ubuntu.
  - Install Oh My Zsh in Ubuntu.
  - Install Zsh-Autosuggestions for Oh My Zsh in Ubuntu.
  - Configure Oh My Zsh in Ubuntu.
- Install Docker Desktop.
- Configure File Explorer:
  - Show file extensions.
  - Open file explorer to This PC.
  - Set as background option moved to extended Context Menu.
  - Disable recently opened items from JumpList.
- Microsoft Windows optional features:
  - Disable Windows Media Player.
  - Disable Internet Explorer.
  - Disable Microsoft XPS Document Writer.
  - Disable WorkFolders Client.
  - Enable Windows Sandbox.
- Configure Windows 11 power plan.
- Configure Windows 11 regional format:
  - First day of week: Monday.
  - Short date: 2017-04-05.
  - Long date: Wednesday, 5 April, 2017.
  - Short time: 19:40.
  - Long time: 19:40:07.
- Rename PC.
