# Colour Scheme PaperColor for KDE Konsole

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This is an adaption of the [PaperColor
theme](https://github.com/NLKNguyen/papercolor-theme) for the
[KDE](https://kde.org) terminal emulator [Konsole](https://konsole.kde.org).

Many thanks go to [z2oh](https://github.com/z2oh|z2oh). From his dotfiles
repository the first version of this colour scheme was copied.

## Gallery

<img src="https://raw.github.com/MaxG87/konsole-papercolor/master/screenshots/manpage-and-highligt.png" width="400"/>
<img src="https://raw.github.com/MaxG87/konsole-papercolor/master/screenshots/watson-grey.png" width="400"/>
<img src="https://raw.github.com/MaxG87/konsole-papercolor/master/screenshots/zsh.png" width="400"/>

## Installation

To add this colour scheme to Konsole, copy the colour scheme file to
`.local/share/konsole/`. Then you will be able to select it in the dialogs.

## Description of Colour Codes

This section lists some known usages for the individual colour names. This
makes it much easier to test certain changes.

Colour Name | Known Usage
----------- | -----------
Background | <ul><li>normal background</li></ul>
Color0 | <ul><li>Zsh prompt text's font colour</li><li>Tmux status bar's font colour</li><li>needrestart's box' shadow</li><li>background colour of devices in the output of `ls /dev/sd*`</li></ul>
Color0Intense | <ul><li>Zsh smart suggestions</li></ul>
Color1 | <ul><li>Zsh's failure cross for error exit codes</li><li>_marked as important_ messages' font colour in Mutt's index</li></ul>
Color1Intense | <ul><li>font colour if Zsh cannot find a command</li><li>font colour of remote branches in output of `git log`</li><li>archives (eg `*.xz` or `*.zst`) in output of `ls` or `exa`</li></ul>
Color2 | <ul><li>Tmux' status bar's background colour</li><li>font colour for time specification of `watson status`</li><li>font colour for known commands in Zsh</li></ul>
Color2Intense | <ul><li>font colour of local branches in output of `git log`</li><li>font colour of file names in output of `ag`</li><li>number of current prompt in IPython</li></ul>
Color3 | <ul><li>highlight of matches in `ag`'s search results</li><li>Zsh' prompt bar in dirty Git repositories</li><li>highlight of currently selected messages in Mutt's index</li></ul>
Color3Intense | <ul><li>font colour of tags in output of `git log`</li><li>line numbers' font colour in output of `ag`</li><li>font colour of JSON files in output of `ls` and `exa`</li><li>font colour of devices in the output of `ls /dev/sd*`</li></ul>
Color4 | <ul><li>normal Zsh prompt bar</li></ul>
Color4Intense | <ul><li>patch question's font colour in `git commit -p`</li><li>folder's font colour in output of `ls` and `exa`</li><li>Mutt's header's and footer's font colour</li><li>font colour of sender in Mutt's pager</li></ul>
Color5 | <ul><li>project names' font colour in TDWatson's commands (`watson status`, `watson log`, `watson start`)</li><li>file name's font colour in output of grep</li></ul>
Color5Intense | <ul><li>font colour of image files (`*.jpeg`, `*.png`, etc) in output of `ls` and `exa`</li></ul>
Color6 | <ul><li>package name's font colour in output of `poetry install`</li><li>highlight of currently selected line in htop</li></ul>
Color6Intense | <ul><li>`HEAD` in `git log`</li></ul>
Color7 | <ul><li>Mutt' header's font colour</li><li>deleted entries' font colour in Mutt's index</li><li>needrestart's box' colour</li><li>font colour for services mentioned by needrestart</li></ul>
Color7Intense | <ul><li>font colour of currently selected messages in Mutt's index</li></ul>
ForegroundFaint | <ul><li>Zsh's update message's font colour for commands (e.g. `quarkus`)</li></ul>



## Changelog

- 2023-05-10: Improved colours slightly. Colours appear more clear and not
  greyish. Also, unused colours have signal values now to be directly
  detectable.
- Adaption of Color7 to support a highlighting used by `watson`.
- Adaptions to two colours to support zsh-autosuggestions.
