# open_newtab

Wrapper for macOS's open command to open folder in new tab of Finder instead of new window.

## Note!

After macOS Sierra, you don't need this script to open with new tab.

In Sierra, you can find
**Prefer tabs when opening documents** setting
in **Dock** of **System Preferences**.

To open in new tab, set it **Always**.

> [macOS Sierra: Open folders in new Finder tabs or windows](https://support.apple.com/kb/PH25244)

## Installation

On Mac, you can install scripts by [Homebrew](https://github.com/mxcl/homebrew):

    $ brew tap rcmdnk/rcmdnkpac/open_newtab

If you have [brew-file](https://github.com/rcmdnk/homebrew-file), add following lines to Brewfile:

    tap 'rcmdnk/rcmdnkpac'
    brew 'open_newtab'

then, do:

    $ brew file install

Or if you write like:

    tapall 'rcmdnk/rcmdnkpac'

and do `brew file install`, you will have all useful scripts in
[rcmdnkpac](https://github.com/rcmdnk/homebrew-rcmdnkpac).

Or, simply download the script and set where you like.

## Usage

`open_newtab` is wrapper script for `open` command
and the usage is exactly same as `open`.

To make it easy, use `alias`:

    alias open=open_newtab

in your **.bashrc** or **.zshrc**.
