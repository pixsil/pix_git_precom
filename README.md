# pre-commit file for npm run production in Laravel

## Features

* Runs automatically before commit
* Checks mix-manifest.json for compiled file names
* Check if one of the files is being added to the commit
* Automaticly runs "npm run production" and add compiled files to commit again

## Donate

Find this project useful? You can support me on Patreon

https://www.patreon.com/pixsil

## Installation

Place this file in your hooks dir inside the .git directory. That's all!

Quick install from root folder project:
```
wget -O .git/hooks/pre-commit https://raw.githubusercontent.com/pixsil/pix_git_precom/main/pre-commit
```
