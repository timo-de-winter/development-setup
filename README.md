# Development Setup

A personal reference repository for my local development environment. This repo documents the tools I use day-to-day and provides scripts to automate setting up a new machine.

## What's in this repo

- **Tool references** — A catalog of the development tools I rely on, with notes on configuration and usage.
- **Setup scripts** — Run these on a fresh PC to automatically install and configure everything I need.

## Getting started

Clone the repo and run the setup script. The script will ask you what you want to install, so no worries :).
The command works for both Windows and Linux environments.

```bash
git clone https://github.com/timo-de-winter/development-setup.git && cd development-setup

bash bin/install
```

## Stuff I use
All things that contain a `+` in front of it are installable through the command mentioned above.

### GUI Tools
- **PHPStorm** is my code-editor of choice
- **GitKraken** is my git GUI
- **Fork** is an alternative git GUI I use, since gitkraken can be slow at times
- +**Warp** is my command-line of choice (it has great AI integration capabilities and natural language processing)

### Environment setup
- **WSL2** is what I use to run a lot of projects
- **Laravel Herd** for local windows development environment
- +**Scoop** is a package manager for windows which I use to install stuff
- +**GNU core utils** adds Linux style commands to PowerShell (e.g. `ls`, `grep`, etc.). Installed using Scoop "scoop install uutils-coreutils"

### AI tools
- +**Claude Code** is my 
- +**Chief** is an autonomous PRD agent that breaks projects into tasks and runs Claude Code in a ralph loop. It runs each task in it's own clean context while keeping a shared memory intact.

### CLI tools & aliases
**Tools**
- +**fnm** is a fast node version manager (works better than `nvm` for me, while still working with `.nvmrc` files)
- +**nano** is a terminal text editor

**Aliases**
- +**eza** alias for ls (with icons and git state)
- +**eza** alias for ll (using `-l` with icons and git state)
- +**bat** alias for `cat` (syntax highlighting)
- +**zoxide** alias for `cd` (smart directory switching)
- +**art** alias for `php artisan`
