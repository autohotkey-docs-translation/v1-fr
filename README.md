# AHK-Docs_FR
Traduction française de la documentation d'AutoHotkey

# How to contribute
The folder `english` aims to be the same as a copy of the [original docs repository commit #5e18a14](https://github.com/Lexikos/AutoHotkey_L-Docs/commit/5e18a14fb51344d63cf354159e259d02e1c1e2d6)

In order to maintain consistency, the documents to be translated need to be "frozen in time" so we can later know what is out of date when everything has been translated.

Do not commit anything to `english`. If a file has been translated, save and commit it under `french` in its corresponding folder.

If a file is only partly translated, indicate it in the filename. For example `Welcome.htm` could be `Welcome.part.htm` or `Welcome.htm.part`.

The goal is to keep track of what has been translated from the "frozen copy" of the original documentation, such that if a corresponding file under `english` does not exist under `french` then it has not yet been translated.

**Note:** Do not translate the file names or html code, such as `<tags>`, `attributes="some value"`, anchors `#my_page_section`, etc.

## Steps to translate a file
1. clone this repository
2. copy a file from `english` that you aim to translate, to `french` (preserving relative paths, eg. `french/docs/AutoHotkey.htm`)
3. **Only** commit translated files under `french/`, do not commit files in `english/`.
   > If a file is only partly translated, indicate it in the file name. ex. `french/docs/AutoHotkey.part.htm` or `french/docs/AutoHotkey.htm.part`.

## Tools
- [**OmegaT**](https://omegat.org/) - Free open-source translation memory tool, computer-assisted translation (CAT) software
- [**Microsoft Terminology Translation**](https://www.microsoft.com/en-us/language) - Useful for when you need a computer-term in a different language. These are used my Microsoft themselves for things like Windows, Office, Skype, Xbox, Bing, etc.
  - You can download *.tbx glossary files here to help with CAT software: 
  https://www.microsoft.com/en-us/language/Terminology
- [**POEdit**](https://poedit.net/) - Translation editor, free version available

# Style d'écriture
**Rajouter ici les choix faits lors de la traduction afin de garder un style homogène et cohérent**

AutoHotkey est utilisé comme nom propre masculin

On préfère une reformulation à l'utilisation de "tu" ou "vous" puisqu'on n'a pas la neutralité de "you" en français

"hotkey" n'est pas traduit puisque le concept inclut plus que "raccourci clavier" et utilisé au féminin

"hotstring" pareil et utilisé au masculin

"OutputVar" est traduit par "VarSortie" (rq : pas forcément une bonne idée)

"InputVar" est traduit par "VarEntree"

<kbd>Shift</kbd> est traduit par <kbd>Maj</kbd>

<kbd>Caps Lock</kbd> est traduit par <kbd>Verr Maj</kbd>

<kbd>Backspace</kbd> est traduit par <kbd>Suppr arrière</kbd>

"Mouse Wheel" est traduit par "Roulette de la souris"

"Joystick" restera "Joystick", et non des termes qui peuvent etre ambigu: "gâchettes", "stick", "bouton de tranche", etc.

"Key(s)" est traduit par "Touche(s)" et non "clé(s)" ou "bouton(s)".

"Numpad" est traduit par "Pavé numérique".
