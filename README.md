# Ulauncher Spell

## Requirements

-   [Ulauncher 5.0+](https://ulauncher.io/)

## Installation

Open Ulauncher Preferences, go to the "Extentions tab", click "Add Extension", copy-paste the following link and click the "Add" button:

```
https://github.com/lohenyumnam/ulauncher-spell
```

## Custom dictionaries

### Configure vocabulary

By default, Spell support Deutsch, English, Espanol, Francais, Italiano, Nederlands, and Norsk. But only English and English_uk are activated by default. You can modify the list of active vocabularies via the "Vocabulary" section of the extension preference.

Active your favourate vocabulory by adding it to the "Active vocabulary" field as comma-delimted text on the `Ulauncher->Preferences->Extensions->Spell` page:

Notes:

-   The more vocabularies activated, the slower the search is. Speed is often not an issue on modern computers. But in case you feel laggy. Consider deactivating the vocabularies you don't need, or switch to the 'regex' matching method.

## Development

1. (Exit Ulauncher if it's running) Run
   `ulauncher --no-extensions --dev -v`

2. (In another terminal) Run

```
VERBOSE=1 ULAUNCHER_WS_API=ws://127.0.0.1:5054/ulauncher-1dictionary PYTHONPATH=$HOME/src/Ulauncher /usr/bin/python3 $HOME/.local/share/ulauncher/extensions/com.github.lohenyumnam.spell/main.py
```

## References

-   [JUST WORDS!](http://www.gwicks.net/dictionaries.htm)
-   [Linguee](https://www.linguee.com/)
-   [Merriam-Webster](https://www.merriam-webster.com/)
-   [SpanishDict](https://www.spanishdict.com)
-   [Collins](https://www.collinsdictionary.com/)
-   [Google Translate](https://translate.google.com/)
