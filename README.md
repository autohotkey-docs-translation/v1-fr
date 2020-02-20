# AHK-Docs_FR
Traduction française de la documentation d'AutoHotkey

# How to contribute
Folder `english` aims to be the same as [original documentation repository](https://github.com/Lexikos/AutoHotkey_L-Docs)

Only commit a file to `english` if the corresponding file has been translated in `french`, and commit both files in the same commit

The goal is to keep track of progress by making use of (for example) `git status` by always having `french` an exact translation of `english`,
as well as in the future to keep track of where the original documentation was changed.

1. clone this repository
2. copy [original documentation repository](https://github.com/Lexikos/AutoHotkey_L-Docs) contents into cloned `english`
3. choose a file to translate (let's say `english/docs/AutoHotkey.htm`) and copy it into `french` (preserving relative paths of course so `french/docs/AutoHotkey.htm`)
4. translate copied file to french
5. commit **only** files translated (`english/docs/AutoHotkey.htm` and `french/docs/AutoHotkey.htm`),
especially meaning: do not commit files in english that weren't translated or which translation wasn't updated
