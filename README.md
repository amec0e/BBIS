# BBIS
BugBounty Install Script Version: `1.6`

Raspberry Pi BugBounty Install Script Version: `1.5`

## Description:

A script I wrote to help me automate the installation of tools I use for hunting on a fresh Ubuntu/Raspberry Pi 4 install.


## Usage:

```
. ./BBIS
```

You do not need to use `sudo` unless you absolutely need to for some reason. The script will `sudo` only the parts needed to install the tools or requirements.

### Note For Oh-My-Zsh Users:

Oh-my-zsh by default ships with the plug-in (git) enabled. All this does is add a bunch of alias's for git which one of which is gau `git add --update` 

### Solution:

Either remove git from the plugins= in your .zshrc file or rename the alias for gau before running the script to avoid conflicts. 

## Tools:

 - Anew
 - Amass
 - Aquatone
 - Arjun
 - Crawpy
 - Feroxbuster
 - Ffuf
 - Gau
 - GetJS
 - Gitjacker (Not available in the Pi Version)
 - GitTools
 - LinkFinder
 - Httprobe
 - SecLists + Assetnote Top 1m Parameters

## Requirements: (All included)

 - python3-pip
 - git
 - golang
 - chromium-browser
 - build-essential (just in case)
