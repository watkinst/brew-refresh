# Brew-Refresh
A bash script that updates Homebrew, upgrades Homebrew formulae and optionally cleans up any outdated Homebrew formulae.

## Motivation
Creating an easy way to keep Homebrew and its installed formulae up-to-date.

## Installation
1. Save the script in a file named `brewRefresh` in your home `~` directory (or alternate location).
1. Make the file executable by running `chmod 700 brewRefresh` in the directory where you saved the file.

## Usage
Run `./brewRefresh` in a terminal opened from your home directory (or `<path-to-file>/brewRefresh` if you saved the script to an alternate location). This will:
  - Update Homebrew
  - Upgrade all outdated Homebrew formulae

### Optional Arguments

- `-h | --help` - Display help
- `-d | --debug` - Enable debug mode
- `-c | --cleanup` - Enable brew cleanup

## License
MIT License
https://choosealicense.com/licenses/mit/
