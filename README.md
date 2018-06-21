↑# TheoTown-translation
Here everybody can help to localize TheoTown to other languages.

Every directory contains a values.xml file. The corresponding languages are:</br>
values-ca: Catalan</br>
values-cs: Czech</br>
values-de: German <- Always up to date</br>
values-es: Spanish</br>
values-fr: French</br>
values-hu: Hungary</br>
values-in: Indonesian</br>
values-it: Italian</br>
values-ja: Japanese</br>
values-ko: Korean</br>
values-ms: Malay, Indonesian</br>
values-nl: Dutch</br>
values-pl: Polish</br>
values-pt: Portuguese</br>
values-pr: Pirate</br>
values-ru: Russian</br>
values-sr: Serbian</br>
values-th: Thai</br>
values-tr: Turkish</br>
values-uk: Ukrainian</br>
values-zh-rTW: Traditional Chinese</br>
values-zh: Chinese</br>
values: English (default language) <- Always up to date</br>

For more two letter language codes see http://www.loc.gov/standards/iso639-2/php/code_list.php
You might just add an apropriate directory in order to add a new language.
English and German translations will always be up to date. The others can be built from them.

How translation works:</br>
Each values.xml file contains lines of the form<br>
<em>\<tagname\></em>"My translation"<em>\</tagname\></em><br>
You have just to translate the part in between (here "My Translation"). Special characters like \n might be used to indicate a new line.
When your translation is done, make sure to create a 'pull request' so it can be merged to main branch. 
If you forget to do that step your translation won't be added to the main branch. Follow 2kluvu to find some great stuff.
