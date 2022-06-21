# TheoTown-translation #
Here *anybody* can help to localize TheoTown to other languages.


## For translators ##

### How translation works ###
Each `values.xml` file contains lines of the form:<br/>
`<tagname>"My translation"</tagname>`<br/>
You have just to translate the part in between (here "My Translation"). Special characters like `\n` might be used to indicate a new line. When your translation is done, **make sure to create a 'pull request'** so it can be merged to main branch. If you forget to do that step your translation won't be added to the main branch.

### Languages ###
Every directory contains a `values.xml` file. The corresponding languages are:
- values-b+fil: Filipino
- values-eu: Basque
- values-ca: Catalan
- values-cs: Czech
- values-de: German ← **Always up to date**
- values-es: Spanish
- values-fr: French
- values-hu: Hungary
- values-in: Indonesian
- values-it: Italian
- values-ja: Japanese
- values-ko: Korean
- values-lt: Lithuanian
- values-ms: Malay
- values-nl: Dutch
- values-pl: Polish
- values-pt: Portuguese
- values-ru: Russian
- values-sr: Serbian
- values-th: Thai
- values-tr: Turkish
- values-uk: Ukrainian
- values-vi: Vietnamese
- values-zh-rHK: Hong Kong Chinese
- values-zh-rTW: Traditional Chinese
- values-zh: Chinese
- values: English (*default language*) ← **Always up to date**<br/>

For more two letter language codes see [ISO 639-1](http://www.loc.gov/standards/iso639-2/php/code_list.php). You might just add an apropriate directory in order to add a new language. English and German translations *will always be up to date*. The others can be built from them.

### Escaping characters ###
Certain characters cannot be written directly within the xml file. You will have to replace them according to the following table:
Character | Escaped form
--|--------------------------
" | \&quot;
' | \&apos;
< | \&lt;
\> | \&gt;
& | \&amp;

In Json based translations you will only have to replace " by \\"



## For developers ##
### Grab script ###
There's a `grab.sh` script included that can be used to grab current translations files from the project directory automatically (developer only). For that to work you have to setup a local TheoTown symbolic link to your TheoTown project directory. To do this, execute a command like the following (here assuming running WSL):
```sh
ln -s /mnt/c/Users/User/StudioProjects/TheoTown66 TheoTown
```
