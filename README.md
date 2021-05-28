# AHK-Docs_FR
French translation of AutoHotkey's documentation

# How to contribute
1. Ask joedf in the forum (via [PM](https://www.autohotkey.com/boards/ucp.php?i=pm&mode=compose&u=55) or [thread](https://www.autohotkey.com/boards/viewtopic.php?f=81&t=936)) to get write access to this project
2. Download and run [OmegaT](https://omegat.org/)
3. Click in the menu bar on Project > Download Team Project...
4. Enter `https://github.com/ahkscript/AHK-Docs_FR.git` in the first input field
5. Specify your new local project folder in the next field
6. Click on OK

At some point during the synchronization you will be asked for your GitHub username and password. You only need to enter this information once.

That's it. Now you can translate as you like. Your new translations will be uploaded automatically on a regular basis and at various events such as save, close, etc. If you want to check the current translated state of the document, click on Project > Create Translated Documents and then on Project > Access Project Contents > Current Target Document. When you think it's ready for publishing for now, click on Project > Commit Target Files and let us know via PM, so we can publish the docs. If you have questions, feel free to ask us.

## Tools
- [**OmegaT**](https://omegat.org/) - Free open-source translation memory tool, computer-assisted translation (CAT) software
  - [Google Translator without API key](https://sourceforge.net/projects/omegat-gt-without-api-key/files/) - Plugin for Google Translate service, without needing an API key.
  - [More plugins](https://sourceforge.net/p/omegat/wiki/Plugins/)
- [**Microsoft Terminology Translation**](https://www.microsoft.com/en-us/language) - Useful for when you need a computer-term in a different language. These are used my Microsoft themselves for things like Windows, Office, Skype, Xbox, Bing, etc.
  - You can download *.tbx glossary files here to help with CAT software: 
  https://www.microsoft.com/en-us/language/Terminology

# Style d'écriture
**Rajouter ici les choix faits lors de la traduction afin de garder un style homogène et cohérent**

**AutoHotkey** est utilisé comme nom propre masculin.

On préfère une reformulation à l'utilisation de "**tu**" ou "**vous**" puisqu'on n'a pas la neutralité de "you" en français.

Si vous n'êtes pas certain du nom d'une certaine touche, vous pouvez vous référer à: https://fr.wikipedia.org/wiki/Clavier_d%27ordinateur#Touches_les_plus_communes

## La traduction pour certains termes (Conventions)
| English                | Français                 | Commentaire |
|------------------------|--------------------------|-------------|
| Hotkey                 |                          | Ceci n'est pas traduit puisque le concept inclut plus que "raccourci clavier" et utilisé au féminin. |
| Hotstring              |                          | Pareil et utilisé au masculin. |
| OutputVar              | VarSortie                | rq : pas forcément une bonne idée |
| InputVar               | VarEntree                |             |
| <kbd>Shift</kbd>       | <kbd>Maj</kbd>           | Strictment pour le nom de la touche comme tel |
| <kbd>Caps Lock</kbd>   | <kbd>Verr Maj</kbd>      | Pareil      |
| <kbd>Backspace</kbd>   | <kbd>Suppr arrière</kbd> | Pareil      |
| <kbd>Insert</kbd>      | <kbd>Inser</kbd>         | Pareil      |
| <kbd>Scroll Lock</kbd> | <kbd>Arrêt défil</kbd>   | Pareil      |
| <kbd>Page Up</kbd>     | <kbd>Page ↑</kbd>        | Pareil      |
| <kbd>Page Down</kbd>   | <kbd>Page ↓</kbd>        | Pareil      |
| <kbd>Del</kbd>         | <kbd>Suppr</kbd>         | Pareil      |
| <kbd>Control</kbd>     | <kbd>Ctrl</kbd>          | Pareil      |
| <kbd>AppsKey</kbd>     | <kbd>≣ Menu</kbd>        | Pareil      |
| Mouse Wheel            | Roulette de la souris    |             |
| Joystick               |                          | Restera le meme, et non des termes qui peuvent etre ambigu: "gâchettes", "stick", "bouton de tranche", etc. |
| Key(s)                 | Touche(s)                | ... et non "clé(s)" ou "bouton(s)". |
| Numpad                 | Pavé numérique           |             |
| <kbd>Numpad*</kbd>     | <kbd>Pavnum*</kbd>       | Le prefix a utiliser pour les touches du pavé du numérique. Par exemple, <kbd>NumpadHome</kbd> devient <kbd>PavnumDébut</kbd> |
| Modifier Key(s)        | Touche(s) de combinaison |             |
| Note:                  | Remarque:                | "Notez (bien):" pourait être utilisé aussi |
| Deprecated             | Déconseillé              |             |
| Scan Code              | Code de Balayage         |             |
| (keyboard/mouse) hook  | hook (clavier/souris)    | Ce terme (un anglisisme) ne se traduit pas par "crochet" car c'est un terme spécifique à la programmation. |
