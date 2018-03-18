# Brew-Refresh
A bash script that updates and optionally cleans up any outdated Homebrew formulae.

## Motivation
I got tired of having to remember to periodically run all of the individual Homebrew commands required to keep my installed formulae up-to-date.

## Installation
1. Save the script in a file named `brewRefresh` in your home `~` directory.
1. Make the file executable by running `chmod 700 brewRefresh`.

## Usage
1. To upgrade all outdated Homebrew formulae, in your home `~` directory, run `./brewRefresh`.
1. To upgrade all outdated Homebrew formulae and clean up (remove) all outdated versions, in your home `~` directory, run `./brewRefresh true`.

## License
MIT License
https://choosealicense.com/licenses/mit/
