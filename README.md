JamfLog for Sublime Text
========================

[![GitHub license](https://img.shields.io/github/license/jorks/sublime-jamflog.svg)](https://github.com/jorks/sublime-jamflog/blob/master/LICENSE) [![GitHub tag](https://img.shields.io/github/tag/jorks/sublime-jamflog.svg)](https://github.com/jorks/sublime-jamflog/tags)

[Jamf Log](http://github.com/jorks/sublime-jamflog) is a [Sublime Text](http://www.sublimetext.com/) syntax highlighter for [Jamf Pro](http://jamf.com) server logs.

The plugin makes log files downloaded from a Jamf Pro server easier to read for humans!

Installation
------------

The recommended way to install and update this package is using [Package Control](https://packagecontrol.io/). **09/08/2021: Submission Pending**

0. Open the command palette and search `Install Package Control`
1. Open the command palette and search `Package Control: Install Package`
2. Search for `JamfLog` and install the latest version. 

If you want to install directly from the GitHub repository:

0. Open the command palette and search `Install Package Control`
1. Open the command palette and search `Package Control: Add Repository`
2. Enter: `https://github.com/jorks/sublime-jamflog`
3. Open the command palette and search `Package Control: Install Package`
4. Search for `JamfLog` and install the latest version. 


If you prefer to install this package manually, you can `git clone` this repo or extract the ZIP archive into your Sublime Text `Packages` folder.

JamfLog works with Sublime Text 3 & 4 for macOS, Windows and Linux with 99% of testing performed on macOS.

Usage Tips
----------

You can modify defaults in the JamfLog preferences file. Sublime Text's Command Palette is your best friend - familiarise yourself with the keyboard shortcut: 

- Mac: `Cmd+Shift+P`
- Win: `Ctrl+Shift+P`

Common commands when working with log files:

- `Set Syntax: JamfLog`
- `Word Wrap: Toggle`
- `Code Folding: Fold/Unfold All` (hides all the stack traces)

The JamfLog syntax highlighter looks for files that have the `.log` extension. This has the potential to be annoying if you work with multiple `.log` files from other software vendors. Sorry.

License
-------

sublime-jamflog (JamfLog) is licensed under the MIT license. [LICENSE](https://raw.githubusercontent.com/jorks/sublime-jamflog/master/LICENSE)


Screenshot
----------

![screenshot](images/JamfLogExample.png)