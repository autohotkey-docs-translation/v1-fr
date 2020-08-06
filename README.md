# AHK-Docs_FR
Traduction française de la documentation d'AutoHotkey

# How to contribute
The folder `english` aims to be the same as a copy of the [original docs repository commit #5e18a14](https://github.com/Lexikos/AutoHotkey_L-Docs/commit/5e18a14fb51344d63cf354159e259d02e1c1e2d6)

In order to maintain consistency, the documents to be translated need to be "frozen in time" so we can later know what is out of date when everything has been translated.

Do not commit anything to `english`. If a file has been translated, save and commit it under `french` in its corresponding folder.

If a file is only partly translated, indicate it in the filename. For example `Welcome.htm` could be `Welcome.part.htm` or `Welcome.htm.part`.

The goal is to keep track to keep track of what has been translated from the "frozen copy" of the original documentation, such that if a corresponding file under `english` does not exist under `french` then it has not yet been translated.

1. clone this repository
2. copy a file from `english` that you aim to translate, to `french` (with `part` in the filename, if only partly translated as mentioned above).
  - eg. file to translate (let's say `english/docs/AutoHotkey.htm`) and copy it into `french` (preserving relative paths of course so `french/docs/AutoHotkey.htm`)
3. commit **only** files translated (or partly) as ex. `french/docs/AutoHotkey.htm`,
mainly meaning: do not commit files in `english`.

# Style d'écriture
**Rajouter ici les choix faits lors de la traduction afin de garder un style homogène et cohérent**

AutoHotkey est utilisé comme nom propre masculin

On préfère une reformulation à l'utilisation de "tu" ou "vous" puisqu'on n'a pas la neutralité de "you" en français

"hotkey" n'est pas traduit puisque le concept inclut plus que "raccourci clavier" et utilisé au féminin

"hotstring" pareil et utilisé au masculin

"OutputVar" est traduit par "VarSortie" (rq : pas forcément une bonne idée)

"InputVar" est traduit par "VarEntree"
