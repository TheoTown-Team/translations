# TheoTown-translation 
Here *anybody* can help to localize TheoTown to other languages.

---

## Languages:
Every directory contains a `values.xml` file. The corresponding languages are:
- values-ca: Catalan
- values-cs: Czech
- values-de: German <-- **Always up to date**
- values-es: Spanish
- values-fr: French
- values-hu: Hungary
- values-in: Indonesian
- values-it: Italian
- values-ja: Japanese
- values-ko: Korean
- values-ms: Malay, Indonesian
- values-nl: Dutch
- values-pl: Polish
- values-pt: Portuguese
- values-pr: Pirate
- values-ru: Russian
- values-sr: Serbian
- values-th: Thai
- values-tr: Turkish
- values-uk: Ukrainian
- values-zh-rTW: Traditional Chinese
- values-zh: Chinese
- values: English (*default language*) <-- **Always up to date**

For more two letter language codes see [ISO 639-1](http://www.loc.gov/standards/iso639-2/php/code_list.php). You might just add an apropriate directory in order to add a new language. English and German translations *will always be up to date*. The others can be built from them.

---

## How translation works:
Each `values.xml` file contains lines of the form:
`<tagname>"My translation"</tagname>`
You have just to translate the part in between (here "My Translation"). Special characters like `\n` might be used to indicate a new line. When your translation is done, **make sure to create a 'pull request'** so it can be merged to main branch. If you forget to do that step your translation won't be added to the main branch.
