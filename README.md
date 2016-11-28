# theotown-translation
Here everybody can help to localize TheoTown to other languages.

Every directory contains a values.xml file. The corresponding languages are:
values: English (default langauge);
values-cs: Czech;
values-de: German;
values-fr: French;
values-pl: Polish;
values-zh: Chinese;
values-zh-rTW: Traditional Chinese;

For more two letter language codes see http://www.loc.gov/standards/iso639-2/php/code_list.php
You might just add an apropriate directory in order to add a new language.
English and German translations will always be up to date. The others can be built from them.

How translation works:
Each values.xml file contains lines of the form
<tagname>My translation</tagname>
You have just to translate the part in between (here „My Translation“). Special characters like \n might be used to indicate a new line.
