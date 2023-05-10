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
Color0 | <ul><li>Schriftfarbe im ZSH-Prompt-Text und in der Tmux-Status-Zeile</li><li>Schatten der Box in needrestart</li><li>Hintergrundfarbe der Geräte bei `ls /dev/sd*`</li></ul>
Color0Intense | <ul><li>ZSH Smartsuggestions</li></ul>
Color1 | <ul><li>ZSH-Kreuz bei [[ $? -ne 0 ]]</li><li>Schriftfarbe markierter Einträge in Mutts Index</li></ul>
Color1Intense | <ul><li>ZSH nicht gefundener Befehl</li><li>Angaben nicht-lokaler Branches `git log`</li><li>Archive bei ls oder exa</li></ul>
Color2 | <ul><li>Hintergrundfarbe der Tmux-Status-Zeile</li><li>Schriftfarbe für Zeitangaben in `watson status`</li><li>bekannter Befehl in ZSH</li></ul>
Color2Intense | <ul><li>lokale Branchangaben in `git log`</li><li>Dateinamen in Ausgabe von ag</li><li>Prompt-Nummer in IPython</li></ul>
Color3 | <ul><li>Hervorhebungen der Treffer bei Suchen mit `ag`</li><li>ZSH-Prompt-Balken in Git-Repositories mit Änderungen</li><li>Hervorhebung der ausgewählten Zeile in Mutts Index</li></ul>
Color3Intense | <ul><li>Tagangaben in `git log`</li><li>Zeilennummern in Ausgabe von ag</li><li>JSON-Dateien bei ls und exa</li><li>Schriftfarbe der Gerätenamen bei `ls /dev/sd*`</li></ul>
Color4 | <ul><li>normaler ZSH-Prompt-Balken</li></ul>
Color4Intense | <ul><li>Patch-Frage in `git commit -p`</li><li>Ordner bei ls und exa</li><li>Schriftart in Kopf- und Fußzeilen Mutts</li><li>Absender in Mutts Pager (E-Mail-Ansicht)</li></ul>
Color5 | <ul><li>Projektname in den TDWatson-Befehlen status, log und start</li><li>Dateinamen bei grep</li></ul>
Color5Intense | <ul><li>Bilddateien (JPEG, PNG, GIF) bei ls oder exa</li></ul>
Color6 | <ul><li>Paketnamen in Ausgabe von `poetry install`</li><li>Ausgewählte Zeile in htop</li></ul>
Color6Intense | <ul><li>`HEAD` in `git log`</li></ul>
Color7 | <ul><li>Mutt Kopfzeile</li><li>Mutt Schriftfarbe bei gelöschten Einträgen im Index</li><li>Kastenfarbe in needrestart</li><li>Schriftfarbe der Dienste in needrestart</li></ul>
Color7Intense | <ul><li>In Mutt die Farbe der Schrift des aktuell hervorgehobenen Eintrages im Index</li></ul>
ForegroundFaint | <ul><li>Kommandonamenschriftfarbe in ZSHs Update-Nachricht (z.B. '`quarkus`')</li></ul>



## Changelog

- Adaption of Color7 to support a highlighting used by `watson`.
- Adaptions to two colours to support zsh-autosuggestions.
