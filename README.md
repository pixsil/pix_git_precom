# pre-commit file for npm run production in Laravel - Webpack version

This is the old verion to use with webpack. For Laravel 9 and above use:

https://github.com/pixsil/git-pre-commit-vite
 
## Features

* Runs automatically before commit
* Checks mix-manifest.json for compiled file names
* Checks if one of the files is being added to the commit
* Automatically runs "npm run production" and add compiled files to commit again

## Donate

Find this project useful? You can support me on Patreon

https://www.patreon.com/pixsil

## Installation

Place this file in your hooks dir inside the .git directory. That's all!

Quick install from root folder project:
```
mkdir -p .git/hooks && wget -O .git/hooks/pre-commit https://raw.githubusercontent.com/pixsil/pix_git_precom/main/pre-commit && chmod +x .git/hooks/pre-commit
```
